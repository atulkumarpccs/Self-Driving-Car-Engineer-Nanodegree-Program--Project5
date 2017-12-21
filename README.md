# Project 5 : Vehicle Detection and Tracking
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

The second  assignement project  in Term 1 for submission. 


[Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013)

In this project, your goal is to write a software pipeline to identify vehicles in a video from a front-facing camera on a car. The test images and project video are available in the project repository 
<https://github.com/udacity/CarND-Vehicle-Detection>

## Submission Requirment :
 1.Writeup
 
 2.Code (or a Jupyter notebook)
 
 3.Example output images. 
 
 4.Output Video.
 
 ### Acceptance Criteria :
 <https://review.udacity.com/#!/rubrics/322/view>
 
 ### Setup Environmet :
 1. Set up `Starter Kit Installation`
 
   setup by using Anaconda
   <https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md>
   
 2. TensorFlow
If you have access to a GPU, you should follow the TensorFlow instructions for installing TensorFlow with GPU support.

Once you've installed all of the necessary dependencies, you can install the tensorflow-gpu package:
```sh
pip install tensorflow-gpu
```
 ```sh
3. Open the Anaconda Command Prompt.
   example C:\Users\Atul\Anaconda3>
  
4. Run command >>activate carnd-term1

5. Go to the project_submission directory

6. Run >>jupyter notebook P4.ipynb

7. Run shell one by one 

8. Output video take time wait :)

```

Amazon Web Services
Instead of a local GPU, you could use Amazon Web Services to launch an EC2 GPU instance. (This costs money.)

Follow the Udacity instructions to launch an EC2 GPU instance with the udacity-carnd AMI.
Complete the Setup instructions. 

 ### Build Steps :
 ```sh
 1. All steps are based on windows 10 environement.
 
 2. Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier.
 
 3. Optionally, you can also apply a color transform and append binned color features, as well as histograms of color, to your HOG       feature vector.
 
 4. Note: for those first two steps don't forget to normalize your features and randomize a selection for training and testing.
 
 5. Apply a perspective transform to rectify binary image ("birds-eye view").
 
 6. Implement a sliding-window technique and use your trained classifier to search for vehicles in images.
 
 7. Run your pipeline on a video stream (start with the test_video.mp4 and later implement on full project_video.mp4) and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
 
 8. Estimate a bounding box for vehicles detected.
 
 ```  
   
 ### Known Issues :
 ```sh
 1.Set up is not done for personal Linux environment.
 
 2.Some of package for python are installed manually.
 
 3.AWS setup is not working as per support project so done locally.
 ```
 
