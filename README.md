# iHack 2022 - Automatic Image Clustering Challenge


## Overview

This repository showcases my participation in the "iHack 2022" hackathon challenge, conducted by IIT Bhilai in association with Infineon Technologies. The hackathon took place on 15th and 16th October 2022, and I was part of the team that participated in the track:

- Track: Automatic Image Clustering

## About the Challenge

The "iHack 2022" hackathon was organized by IIT Bhilai Innovation and Technology Foundation (IBITF). The goal of our participation was to tackle the challenge related to automatic image clustering.

## Team

- [Lahari Sreeja]
- [Dommati Rohith]
## Introduction

For the "iHack 2022" Automatic Image Clustering Challenge, our team focused on creating an innovative solution to cluster images containing group or individual people based on the faces present within them.

## Solution Overview

### Face Detection with MTCNN

We employed the Multi-task Cascaded Convolutional Networks (MTCNN) model for face detection. MTCNN is known for its robustness in detecting faces within images. We utilized MTCNN to locate and extract faces from each image in our dataset.

### Face Encodings

Once we had the extracted face images, we proceeded to generate face encodings. Face encodings are numerical representations of facial features and are essential for comparing and identifying similarities among faces. We used deep learning techniques to compute these face encodings for each face image in our dataset.

### Clustering Algorithms

#### K-Nearest Neighbors (KNN)

To group similar faces together, we implemented the K-Nearest Neighbors (KNN) algorithm. KNN is a simple yet effective clustering technique that identifies similar data points based on their proximity in feature space. In our case, it helped us cluster faces with similar encodings. This approach allowed us to group individual or group images based on the faces present in them.

#### Density-Based Spatial Clustering of Applications with Noise (DBSCAN)

In addition to KNN, we utilized the Density-Based Spatial Clustering of Applications with Noise (DBSCAN) algorithm. DBSCAN is particularly useful for clustering when the number of clusters is not known in advance. It helped us identify clusters of faces that might not have been apparent through a fixed K value. DBSCAN's ability to handle noise and outliers was also advantageous in our scenario.


This project showcases our team's proficiency in image processing, deep learning, and clustering techniques, which can have practical applications in various domains like social media image organization, security, and more.

## Acknowledgments

I would like to express my gratitude to the organizers of "iHack 2022," IIT Bhilai, and Infineon Technologies for providing this exciting opportunity.

## Achievements
!Hackathon certificate[https://drive.google.com/file/d/1G-v2Q2djX60y4AmkfFE0irh4yP1JD8Q7/view]

