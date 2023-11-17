# DCGAN-to-EMNIST

Train a DCGAN to generate images from noise. Use the EMNIST(Extended MNIST)
database to learn the GAN
Network.
[Discriminator in DCGAN:-
i. if roll no. % 2 == 0: use VGG11 as a discriminator.
ii. if roll no. % 2 == 1: use Resnet 56 as a discriminator.]
Perform the following tasks: [20 marks for training GAN]
a. Uniformly generate ten noise vectors that act as latent representation vectors, and
generate the images for these noise vectors, and visualize them at

i. After the first epoch.

ii. After n/2 th epoch.

iii. After your last epoch. (say n epochs in total)

and comment on the image interpretation at (i), (ii) and (iii) and can you identify
the images? 

b. Plot generator and discriminator losses for all the iterations. Also display the best-generated
images by the model.[One iteration = forward pass
of a mini-batch]
