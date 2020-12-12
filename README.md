## Image Denoising Using AutoEncoders in Keras and Python

#### Environment Setup:
To run the script, at least following required packages should be satisfied:

* Python 
* Tensorflow
* NumPy 
* MatplotLib

#### Dataset:
Dataset used here is standard MNIST Fashion Dataset, which comprises of 28 x 28 pixel images of 9 different fashion wears labelled from 0-9 as specified below:
* T-shirt     -   0
* Trouser     -   1
* Pullover    -   2
* Dress       -   3
* Coat        -   4
* Sandal      -   5
* Shirt       -   6
* Sneaker     -   7
* Bag         -   8
* Ankle boot  -   9

### Autoencoders:
Autoencoders are an unsupervised learning technique. It is an artificial neural network which performs task of data encoding.
It typically comprises of 3 layers: Input,Hidden,Output.
And has 4 components:
* Encoder
* Bottleneck Layer
* Decoder
* Reconstruction Loss

<img src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/10/1_has2O8b3HAUqvcqqLrlBQA-768x281.png"></img>

For Detailed Explaination, refer : 
[Link](https://towardsdatascience.com/auto-encoder-what-is-it-and-what-is-it-used-for-part-1-3e5c6f017726)

#### Output: 
Denoising Images by adding 50% noise to training and testing data
Input and Output Image comparision :
![Image](https://github.com/anushkajain97/Image_denoising_using_Autoencoder/blob/master/Output_comparision_image.png)

#### References:
 * [Rhyme - Project: Image denoising using Autoencoder](https://www.coursera.org/learn/autoencoders-image-denoising/home/welcome)
 * [Auto-Encoder: What Is It? And What Is It Used For? (Part 1)](https://towardsdatascience.com/auto-encoder-what-is-it-and-what-is-it-used-for-part-1-3e5c6f017726)
 * [Variational Autoencoders are Beautiful](https://www.compthree.com/blog/autoencoder/)
