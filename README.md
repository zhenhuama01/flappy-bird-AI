# Playing FlappyBird using Keras, Deep Q learning and CNN

# Installation Dependencies:

* Python 2.7
* Keras 2.0
* pygame
* scikit-image

# Algorithm and Techniques

A convolution neural network (CNN) is used to train a agent and make it learn to play the Flappy bird game by itself. The CNN will have multiple hidden layers, convolution layers, pooling layers, and eventually an output layer with a single output for each valid action.

This CNN will be built the Keras platform. A Q-learning algorithm is used to train the CNN. The Q function in this case represents the maximum discounted future reward when the bird performs action a in state s. The specific Q-learning algorithm I used here is the Deep Q-Network [5]. It is a learning algorithm developed by the Google DeepMind team to enable playing games with AI. By using just the screen pixels, receiving a reward associate to the changing game score, the algorithm provide provide a way for a computer to learn to play video games by itself.

# How to Run?

After installing the dependences mentioned in Section “Implementation” in Page 6, download and go into the attached folder “AI_flappy_bird”
In the terminal, type in: python CNN_flappybird.py -m “Run”

If you want to train the network from beginning, delete the model.h5 and run qlearn.py -m "Train"
