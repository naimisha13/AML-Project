# AML-Project
individual project under the Applied Machine Learning 5156 Course

#Image restoration with CNN


ProblemStatement:<br>
In this project, I will be implementing the approach of Learning Deep CNN Denoiser Prior for Image Restoration paper to restore images by using CNN (convolution neural networks) as priors over the images and train it to perform image inpainting and denoising.<br>
<br>
Motivation and Challenges:<br>
The motivation behind taking up this project topic is to mainly surprise my parents with the restored images. I have heard them many times saying that they should have taken better care of the images and stored them digitally. <br>
This project also helped me get a better understanding of CNN concepts which is one of the most important topics in Deep Learning.<br>
The main challenge was to find out hardware that would help me and the compatible libraries for my device. That's when I decided to switch to google colab notebook but to no avail as I exhausted my GPU subscription. Faced the challenge to replicate the results.<br>

Summary of my approach:<br>
Taking inspiration from the Learning with Deep Prior paper and an existing project on GitHub, I have attempted to replicate the approach and added a few steps of my own to achieve the desired result for my image dataset.<br>
This is an unsupervised approach to perform image restoration which got me interested in it and it made the most sense to me. In the selected paper, the authors have proposed a way of using the CNNs to implement image restoration without using a training dataset. Instead they use a Deep Image Prior to perform the task. <br>
This image that is close to the Natural Image has reduced noise in it, But it lacked the desired quality. I decided to add nother layer of deblurring and deconvoluting the image to get a result closer to the Natural Image.<br>

Conclusion:<br>
Though the desired output is not of the quality that I expected to be I learned a lot about Convolution Neural Networs, Priors and in general Image restoration techniques and approaches. I discovered new libraries for the implementation of the same and had fun experimenting with them. <br>
My future work involves exploring other image restoration techniques, learning about working with hardware and CUDA and other techniques that will help me get better results. I also have to work on implementation with the kernels of depth 3 which will help me retain and improve the colour of the images.<br>
