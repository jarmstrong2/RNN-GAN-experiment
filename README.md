# RNN_GAN_experiment
Using the MNIST set to experiment with GANs using RNNs (code provided uses TensorFlow)

![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/faster_transition_smaller.gif)

Model
=====
Following a generic generative adversarial network, the model consists two networks trained in parallel, and sharing weights.
The blue portion of the model is the generator and the green portion is the discriminator. For purposes of clarity the image is
split into quadrants here, but in other experiments the attempt was to split the image into pixels in an attempt to create a 
generator that could create digits pixel by pixel using long range memory. Up to now the best results have occurred with splitting
the image into 16 sections, beyond that the model fails.

![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/model_diagram.jpg)

Generator
---------
![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/model_diagram_gen.jpg)

Discriminator
---------
![alt text](https://github.com/jarmstrong2/RNN_GAN_experiment/blob/master/images/model_diagram_disc.jpg)