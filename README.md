# Neutral-network 

Tensorflow installation method.

Method 1:
pip install matplotlib numpy scipy scikit-image six
pip install tensorflow 

Method 2: 
brew install matplotlib numpy scipy scikit-image six
brew install tensorflow 


#1: pip version dicision python 2 or 3.
#2: brew version depence on gitgub version.

Verify:

1. Run python2.7
2. Test Code
import tensorflow as tf
sess = tf.Session()
print(sess.run(tf.constant('Hello, Guys!')

3. When output show
'Hello, Guys!'

it almost done. ^^
