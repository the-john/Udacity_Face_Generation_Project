# Face Generation Sample Code
This is some interesting jupyter notebook sample code [dlnd_face_generation%20(1).ipynb](https://github.com/the-john/GANs/blob/master/dlnd_face_generation%20(1).ipynb).

Here we create a Deep Convolutional GAN (DCGAN).  We train it on pictures of celebrities, then generate a totally new face from noise.  The output is a bit crude, mainly due to the low resolution of the output images (in my opinion).  But it's an amazing concept.  

We get the celebrity images from [CelebA.html](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). You can get pre-processed image set from here [processed-celeba-small.zip](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip).  Here the images are reduced to 64x64x2 and cropped to the faces only.

This is what some of the celebrity images look like.
![Celebrity PICs](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/Celebrity%20PICs.JPG)

And this is what some of the faces generated from "noise" look like.
![Generated PICs](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/Generated%20PICs.JPG)
