# Handwritten Digit Recognition using Neural Network

<h2>Introduction: </h2>
<p>Handwritten digit recognition using MNIST dataset is a major project made with the help of Neural Network. It basically detects the scanned images of handwritten digits. 
We have taken this a step further where our handwritten digit recognition system not only detects scanned images of handwritten digits but also allows writing digits on the screen with the help of an integrated GUI for recognition.</p>

<h2>Approach: </h2>
<p>We will approach this project by using a three-layered Neural Network. 
<ul>
  <li><b>The input layer: </b>It distributes the features of our examples to the next layer for calculation of activations of the next layer.</li>
  <li><b>The hidden layer: </b>They are made of hidden units called activations providing nonlinear ties for the network. A number of hidden layers can vary according to our requirements.</li>
  <li><b>The output layer: </b>The nodes here are called output units. It provides us with the final prediction of the Neural Network on the basis of which final predictions can be made.</li>
</ul>
A neural network is a model inspired by how the brain works. It consists of multiple layers having many activations, this activation resembles neurons of our brain. A neural network tries to learn a set of parameters in a set of data which could help to recognize the underlying relationships. Neural networks can adapt to changing input; so the network generates the best possible result without needing to redesign the output criteria.</p>

<h2>Methodology: </h2>
<p>We have implemented a Neural Network with 1 hidden layer having 100 activation units (excluding bias units). The data is loaded from a .mat file, features(X) and labels(y) were extracted. Then features are divided by 255 to rescale them into a range of [0,1] to avoid overflow during computation. Data is split up into 60,000 training and 10,000 testing examples. Feedforward is performed with the training set for calculating the hypothesis and then backpropagation is done in order to reduce the error between the layers. The regularization parameter lambda is set to 0.1 to address the problem of overfitting. Optimizer is run for 70 iterations to find the best fit model. </p>
