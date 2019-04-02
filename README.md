## Advanced Lane Finding

Vinh Nghiem

Self-Driving Car Engineer Program

In this project, a software pipeline is written to identify the lane boundaries in a video, along with a detailed writeup of the project.  

The Project
---

The steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`.  The images in `test_images` are for testing the pipeline on single frames.  If you want to extract more test images from the videos, you can simply use an image writing method like `cv2.imwrite()`, i.e., you can read the video in frame by frame as usual, and for frames you want to save for later you can write to an image file.  

Examples of the output from each stage of the pipeline is saved in the folder called `ouput_images`.  The video called `project_video.mp4` is an example of a  video the pipeline works well on.  

Report
---
A detailed writeup of the project is found [here](P4.pdf)


