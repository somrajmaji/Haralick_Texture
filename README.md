                                                 # Haralick_Texture

                             Haralick Texture is used to quantify an image based on texture
                             
 What is a Texture?
 
Texture defines the consistency of patterns and colors in an object/image such as bricks, school uniforms, sand, rocks, grass etc. To classify objects in an image based on texture, we have to look for the consistent spread of patterns and colors in the object’s surface. Rough-Smooth, Hard-Soft, Fine-Coarse are some of the texture pairs one could think of, although there are many such pairs.


What is Haralick Texture?

Haralick Texture is used to quantify an image based on texture. It was invented by Haralick in 1973 and you can read about it in detail here. The fundamental concept involved in computing Haralick Texture features is the Gray Level Co-occurrence Matrix or GLCM.

What is GLCM?

Gray Level Co-occurrence matrix (GLCM) uses adjacency concept in images. The basic idea is that it looks for pairs of adjacent pixel values that occur in an image and keeps recording it over the entire image. Below figure explains how a GLCM is constructed.


                                                Mahotas – Haralick features
                                                
We will see how we can get the haralick features of image in mahotas. Haralick texture features are calculated from a Gray Level Co-occurrence Matrix, (GLCM), a matrix that counts the co-occurrence of neighboring gray levels in the image. The GLCM is a square matrix that has the dimension of the number of gray levels N in the region of interest (ROI). For this we are going to use the fluorescent microscopy image from a nuclear segmentation benchmark.       

Mahotas is a computer vision and image processing library for Python.

