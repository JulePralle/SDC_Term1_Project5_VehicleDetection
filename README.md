# **Self-Driving Car Engineer - Nanodegree** 
## ---Computer Vision---
# Vehicle Detection

---
[//]: # (Image References)

[image1]: ./output_images/chess_cornerDraw_undis_12.jpg "Camera Calibration Chessboard"
[image2]: ./output_images/Undistortion_3.jpg "Undistortion of Image 3"
[image3]: ./output_images/Undistortion_5.jpg "Undistortion of Image 5"
[image4]: ./output_images/warp_7.jpg "Perspective Transform of Image 7"
[image5]: ./output_images/warp_2.jpg "Perspective Transform of Image 2"
[image6]: ./output_images/gray_and_thresh.jpg "Gray Image and Binary"
[image7]: ./output_images/RGB_and_thresh.jpg "RGB Channel and Binary"
[image8]: ./output_images/HLS_and_thresh.jpg "HLS Channel and Binary"
[image9]: ./output_images/color_stack_thresh.jpg "Combined Color Images and Binary"
[image10]: ./output_images/sobels_and_magnitude.jpg "Sobelx, Sobely and their magnitude"
[image11]: ./output_images/direction.jpg "Direction of the Gradient"
[image12]: ./output_images/allcombined.jpg "Combined Color and Gradient Thresholding"
[image13]: ./output_images/histogram.jpg "Histogram of Pixels"
[image14]: ./output_images/SlidingWindows.jpg "Sliding Windows"
[image15]: ./output_images/SearchWindow.jpg "Searching Windows"
[image16]: ./output_images/OriginalwithLaneArea.jpg "Warp back onto original image"
[image17]: ./output_images/ResultImageText_3.jpg "Result of Image 3 with Text"
[image18]: ./output_images/ResultImageText_5.jpg "Result of Image 5 with Text"
[image19]: ./output_images/Summary_1.jpg "Summary of Image 1"
[image20]: ./output_images/Summary_2.jpg "Summary of Image 2"
[image21]: ./output_images/Summary_3.jpg "Summary of Image 3"
[image22]: ./output_images/Summary_4.jpg "Summary of Image 4"
[image23]: ./output_images/Summary_5.jpg "Summary of Image 5"
[image24]: ./output_images/Summary_6.jpg "Summary of Image 6"
[image25]: ./output_images/Summary_7.jpg "Summary of Image 7"
[image26]: ./output_images/Summary_8.jpg "Summary of Image 8"
[image27]: ./output_images/OriginalForThresh.jpg "Original Image for Thresholding"

## Introduction
The goal of this project is to write a software pipeline to identify the vehicles in a video from a front-facing camera on a car. To identify the vehicles first the features of car and non-car images will be extracted by using color conversion and histogram of gradient directions. Secondly, these extracted features will be used to train a classifier which will be able to distinguish between car and non-car features. With this classifier in the end the vehicles in the video will be detected.


The video below shows the result of this project.


![result video](./result_video.gif) 




The goals / steps of this project are the following:
1. 
9. Create a pipeline to executes all the steps above 
10. Summarize all the steps for the test images
11. Discuss the approach, the results and issues of this project



My project includes the following files:
* AdvancedLaneLineDetection.ipynb: Notebook, containing the code 
* result_video.gif: Video, showing the detected lane boundaries
* README.md: Report for summarizing the results
* output_images: Folder, containing all the images in this report 

---
## 1. 

![alt text][image1]

## 2. 

![alt text][image2]
![alt text][image3]


## 3. 


## 4. 

...
## 9. Pipeline
...
Now, I need to create a pipeline which executes all those steps. In the end I just need to run the pipeline to detect vehicles in a given video and output a new video showing the results.

## 10. Summary
The following figures summarize all the steps from above for every single test image. 



## 11. Discussion
