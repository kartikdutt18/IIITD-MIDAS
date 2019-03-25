# IIITD-MIDAS
## Python Problem
**Requirements:**

tweepy==3.3.0

pandas

**Installation:**

pip install tweepy==3.3.0

pip install pandas

**Functionalities:**

(1) Fetch all the tweets(as many as allowed by Twitter API) done by a user twitter handle and dump the responses into        
JSONlines file.

(2) The other part of your script should be able to parse these JSONline files to display the following for every tweet in a 
tabular format.
  
  ● The text of the tweet.

  ● Date and time of the tweet.

  ● The number of favorites/likes.

  ● The number of retweets.

  ● Number of Images present in Tweet. If no image returns None.


(3)Preprocess Text:
  
  ● Remove URLs,hashtags etc.
  
  ● Replace @username with username
  
![alt text](https://github.com/kartikdutt18/IIITD-MIDAS/blob/master/imgs/Screen%20Shot%202019-03-25%20at%2010.44.21%20PM.png)

 Without Hashtags:
![alt text](https://github.com/kartikdutt18/IIITD-MIDAS/blob/master/imgs/Screen%20Shot%202019-03-25%20at%2010.44.37%20PM.png)
  
  
## Computer Vision Problem

**Model Used: Capsule Network**

Reason: Outperforms general CNN architectures such as DenseNet,VGG,Resnet etc.

### Capsule Network:

Hinton: “The pooling operation used in convolutional neural networks is a big mistake and the fact that it works so well is a disaster.”

Internal data representation of a convolutional neural network does not take into account important spatial hierarchies between simple and complex objects.

The key to this richer feature representation is the use of vectors rather than scalers.
 This routing by agreement method is superior than the current mechanism like max-pooling. Max pooling routes based on the strongest feature detected in the lower layer. Apart from dynamic routing, CapsNet talks about adding squashing to a capsule. Squashing is a non-linearity. So instead of adding squashing to each layer like how you do in CNN, you add the squashing to a nested set of layers. So the squashing function gets applied to the vector output of each capsule.The paper introduces a new squashing function. You can see it in image 3.1. ReLU or similar non linearity functions work well with single neurons. But the paper found that this squashing function works best with capsules. This tries to squash the length of output vector of a capsule. It squashes to 0 if it is a small vector and tries to limit the output vector to 1 if the vector is long. The dynamic routing adds some extra computation cost. But it definitely gives added advantage.
 
 **Installations:**
 
pip install torch

pip install torchvision

pip install numpy

pip install pandas

pip install matplotlib

