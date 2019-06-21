# Face Generation Sample Code
This is some interesting jupyter notebook sample code [dlnd_face_generation.ipynb](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/dlnd_face_generation.ipynb).

Here we create a Deep Convolutional GAN (DCGAN).  We train it on pictures of celebrities, then generate a totally new face from noise.  The output is a bit crude, mainly due to the low resolution of the output images (in my opinion).  But it's an amazing concept.  

We get the celebrity images from [CelebA.html](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). You can get pre-processed image set from here [processed-celeba-small.zip](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip).  Here the images are reduced to 64x64x2 and cropped to the faces only.


This is what some of the celebrity images look like.
![Celebrity PICs](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/Celebrity%20PICs.JPG)


And this is what some of the faces generated from "noise" look like.
![Generated PICs](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/Generated%20PICs.JPG)

The entire project is zipped [project-face-generation.zip](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/project-face-generation.zip) and archived [archive.zip](https://github.com/the-john/Udacity_Face_Generation_Project/blob/master/archive.zip) if interested.
