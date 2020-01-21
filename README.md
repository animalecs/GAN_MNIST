# Deep Convolutional Generative Adversarial Network


Implementation of a GAN, using Tensorflow, that generates random handwritten digits based on the MNIST dataset, as described by Google [here].  
The project is composed by two networks: a generator, in charge of generating new images, and a discriminator, in charge of discriminating the fake images from the real ones. 
I've used Google Colab to train the model in order to benefit from the computational power of their servers. The training time per epoch was 170s when using TPU and just 12 seconds when using GPU.

![Image generated on the 100th epoch](https://github.com/animalecs/GAN_MNIST/blob/master/training_images/image_at_epoch_0100.png?raw=true)

[here]: <https://www.tensorflow.org/tutorials/generative/dcgan>

