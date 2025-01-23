# HUMAN_POSE_ESTIMATION_USING_MACHINE_LEARNING
This repository provides implementation for Human Pose Estimation that predicts the location of various human keypoints (joints and landmarks) such as elbows, knees, neck, shoulder, hips, chest etc.

# Software Requirements
* Programming languages : Python
* Deep learning frameworks : TensorFlow, PyTorch
* Libraries : OpenCV, NumPy
* OpenPose

# Proposed Methodology
1. System Design
   * Blaze Pose : Blaze Pose is a high-performance body pose estimation model tailored for mobile real-time applications. It
     enables quick and precise human pose estimation by using a lightweight convolutional neural network architecture to identify
     33 key body points from a single picture or video frame.
   * Key Features :
     1. Two-stage detector-tracker pipeline
        Blaze Pose employs a two-stage procedure in which an initial detector identifies the area of interest where the individual
        is located, and a second tracker forecasts the exact positions of key points within this area.
     2. 3D pose estimation capability
        Blaze Pose can infer 3D coordinates in addition to 2D key point recognition, offering a thorough analysis of body
        movementsin three dimensions.
     3. Mobile device optimization
        Blaze Pose was created with mobile platforms in mind and offers excellent performance without consuming a lot of energy
# Implementation and Result
Following are a ***few human poses*** predicted by the model:-
| Test Image        | Generated Keypoint Skeleton           |
| ------------------- |:----------------------------:|
| <img src="https://github.com/85447/Human-Pose-Estimation/blob/main/SampleImages/sample.jpg" height="495"> | <img src="https://github.com/85447/Human-Pose-Estimation/blob/main/SampleImagesResults/P4.png" height="495"> |
| <img src="https://github.com/85447/Human-Pose-Estimation/blob/main/SampleImages/sample2.jpg" width="320"> | <img src="https://github.com/85447/Human-Pose-Estimation/blob/main/SampleImagesResults/P5.png" width="320"> |
<!-- | <img src="https://github.com/fork123aniket/Encoder-Decoder-based-Video-Captioning/blob/main/input_videos/7NNg0_n-bS8_21_30.gif" width="320"> | a man is performing on a stage | -->
<!-- | ![alt text](https://github.com/fork123aniket/Human-Pose-Estimation/blob/main/images/sample.jpg) | ![alt text](https://github.com/fork123aniket/Human-Pose-Estimation/blob/main/images/sample_result.webp) |
| ![alt text](https://github.com/fork123aniket/Human-Pose-Estimation/blob/main/images/sample2.jpg) | <img src="https://github.com/fork123aniket/Human-Pose-Estimation/blob/main/images/sample2_result.webp" height="395"> |
| <img src="https://github.com/fork123aniket/Encoder-Decoder-based-Video-Captioning/blob/main/input_videos/7NNg0_n-bS8_21_30.gif" width="320"> | a man is performing on a stage | -->
- SOME WEB CAM GENERATED KEYPOINT SKELETON
<img src="https://github.com/85447/Human-Pose-Estimation/blob/main/SampleImagesResults/P3.png" height="495">

