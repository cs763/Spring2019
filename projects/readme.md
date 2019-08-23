<h1>Computer Vision (CS 763) - Spring 2019 Final submitted Projects</h1>

<ol>
  <li><b><a href="https://github.com/vamsi3/pix2pix">pix2pix: Image-to-Image Translation with Conditional Adversarial Networks</a></b><br>
  <i>Vamsi Krishna Reddy Satti</i> <br>
  
  pix2pix uses a conditional generative adversarial network to efficiently design a general-purpose image-to- image translation system. Image-to-image translation involves learning a mapping from images from one distribution to corresponding images in another distribution. Many kinds of problems can be viewed as an image-to-image translation problem, including image colorization, edges to object visualization, style transfer etc. This project is a pytorch implementation of pix2pix on map-sattelite domain translation.
  
 <li><b><a href="https://github.com/scopegeneral/Anatomically-aware-Facial-Expression-Synthesis"> Anatomically-aware Facial Expression Synthesis</a></b> <br>
  <i>Vighnesh Reddy Konda, Middepogu Manoj</i> </br>
  
  To generate continuous expressions, we implemented a GAN conditioning scheme based on Action Units (AU) annotations, which describes in a continuous manifold the anatomical facial movements defining a human expression.

Our implementation allows controlling the magnitude of activation of each AU and combine several of them. Additionally, we trained the model using an unsupervised strategy, that only requires images annotated with their activated AUs, and exploit attention mechanisms that make our network robust to changing backgrounds and lighting conditions.

<li><b><a href="https://github.com/surajsoni5/Context-Aware-Image-Captioning">Context-aware Captions from Context-agnostic Supervision</a></b></br>
  <i>Talluri Sai Teja, Suraj Soni, N Jagadeep Sai</i><br>
  
  A PyTorch implementation of the paper "Context-aware Captions from Context-agnostic Supervision". The objective is to produce pragmatic, context aware descriptions of images (captions that describe differences between images or visual concepts) using context agnositic data (captions that describe a concept or an image in isolation). 

<li><b><a href="https://github.com/Autonise-AI/Text-Recognition">Pixel-Link</a></b><br>
  <i>Mayank Kumar Singh, Renuka Sharma, Nagandla Varun Kumar</i>
  
  In this project, we are attempting to detect all kinds of text in the wild. The technique used for text detection is based on the paper PixelLink: Detecting Scene Text via Instance Segmentation (https://arxiv.org/abs/1801.01315) by Deng et al. The text instances present in the scene images lie very close to each other, and it is challenging to distinguish them using semantic segmentation. So, there is a need of instance segmentation.

<li><b><a href="https://github.com/prashantksharma/neural-network-compression">Neural Network Compression</a></b><br>
  <i>Akhil Gakhar, Prashant Kumar Sharma, Kurapati Hitesh</i><br>
  
  Main objective of this project is to explore ways to compress deep neural networks, so that the state of the art performance can be ahieved over a resource-constrained devices eg. embedded devices.
  
<li><b><a href="https://github.com/youknowwho-07/CV-Project">MonoSLAM</a></b><br>
  <i>Neelesh Verma, Swadha Sanghvi, Maitrey Gramopadhye</i><br>
  
  We present an algorithm to recover 3D trajectory of a camera using feature based sparse slam using a single camera (also called MonoSLAM).
  
  
<li><b><a href="https://github.com/arpit-1110/Bokeh-Effect">Bokeh Effect</a></b><br>
  <i>Yash Khemchandani, Mashkaria Satvik Mehulbhai, Arpit Aggarwal</i><br>
  
  We aim to build a robust model that produces bokeh effect from an input image using Deep Learning without using advanced camera lenses or dual lenses. We approach this problem with GANs for depth estimation of input image. We therefore model the Bokeh mode problem to background-foreground seperation (segmentation) problem.
  
  <li><b><a href="https://github.com/niranjan-v/Depth-Estimation-from-Single-Image">Depth Estimation</a></b><br>
    <i>Sunkesula Sai Praneeth Reddy, Vaddi Niranjan, Mude Chaithanya Naik</i><br>
      Depth Estimation from Single Image using CNN, CNN+FC, CNN-Residual network. We compare the performances of the three approaches.
  
  
  <li><b><a href="https://github.com/msinghal34/Image-Blending-using-GP-GANs">Image Blending using GP-GAN</a></b><br>
    <i>Mayank Singhal, Sanchit Jain, Chinthareddy Sai Charith Reddy</i><br>
 
   Given two images source, destination and a mask, our goal is to blend destination into source in a manner that is visually appealing. We implemented an encoder-decoder network which takes low resolution(64X64) composite image(source cropped onto destination) and generates a low resolution image(64X64) which looks more natural than the composite. Using this low resolution image and using Laplacian pyramid we tried to optimize Gaussian-Poisson Equation (i) by gradient descent, and (ii) by Pyramid Blending.

  <li><b><a href="https://github.com/lalit184/Image2Depth">Image2Depth</a></b><br>
    <i>Sailor Devangkumar Prashantbhai, Vikrant Nagpure, R Shrinivas</i><br>
  
  In this project, we attemp to perform depth prediction from monocular images for Autonomous Driving. We propose to solve this problem by using a multiscale regression CNN.

</ol>
