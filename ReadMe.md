# First Neural Network Project

This is the first project of a series of five projects for the Deep Learning Foundations Nanodegree.

## Project Description

In this project, a Deep Convolutional Neural Network was implemented. The project uses the MNist dataset in order to generate new hand written numbers and the CelebA dataset in order to generate natural looking faces. The intent of the project was to learn how DCGANs are implemented and trained. This was done with specific focus on the interaction between Generator and Discriminator. The two different datasets are used to display strengths and limitations of the chosen DCGAN model.

The skeleton for the project with some instructions were given by Udacity. Thus, not all written code was done by me. This is indicated in text blocks of the notebook and by comments in the code.

## How to use

This quick guide uses Anaconda for a simple way to execute the program. For most people, the required packages will already be installed and the program can be run directly. None the less, here a working setup.

'''
conda create --name face\_gen python=3.6
source active face\_gen
conda install numpy matplotlib pandas glob tensorflow distutils
jupyter notebook dlnd\_face\_generation.ipynb
'''

## Example output

![](https://github.com/KehxD/Face_Generation_DCGAN/image_examples/face_gen_example.png)
![](https://github.com/KehxD/Face_Generation_DCGAN/image_examples/mnist_gen_example.png)

## Additional Notes

* The python notebook code downloads the CelebA and MNist dataset.
