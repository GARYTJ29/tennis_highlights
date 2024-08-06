
# Tennis Analysis

## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. Analyzed data can be extracted to a csv file.
Further analysis like highlights and refree decisions of the match can be made using other models from the extracted data. 

## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python3.11
* ultralytics
* pytorch
* pandas
* numpy 
* opencv
