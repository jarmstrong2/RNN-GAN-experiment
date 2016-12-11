# RNN_GAN_experiment
Using the MNIST set to experiment with GANs using RNNs
![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/faster_transition_smaller.gif)

Model
=====
Following a generic generative adversarial network, the model consists two networks trained in parallel, and sharing weights.
The blue portion of the model is the generator and the green portion is the discriminator.

![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/model_diagram.jpg)

Generator
---------
![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/model_diagram_gen.jpg)

Discriminator
---------
![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/model_diagram_disc.jpg)