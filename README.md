# Data Security by Facial Recognition using Machine Learning
Full Project Report Link: https://docs.google.com/document/d/1e9ylknybVo8HnvHTK54noBGGot29iIVV/edit?usp=sharing&ouid=106835964365631127896&rtpof=true&sd=true
## Problem Statement
Data driven solution for data and user privacy using  face recognition by image processing and machine learning to ensure that data is accessed only by authorized individuals.
## Introduction
• In today’s world due to an increase of security issues, having a solution that helps users to protect their data and devices from unauthorized accesses is essential. <br />
• Users have confidential data stored on their systems which need to be protected in their absence.<br />
• Hence our solution is to propose a solution for the challenges to recognise the real owner of the information that is being displayed on the screen to protect privacy. <br />
## Abstract
• This system aims to provide data security. <br />
• Ensures that data is protected from unauthorized access. <br />
• It enhances confidentiality and protect personal privacy. <br />
• It uses face recognition to detect if a person is present in front of the screen or not, and as soon as the person leaves the screen, it automatically blurs everything slightly, preventing anyone to have a look. <br />
• It also blurs the screen completely if it detects a different face, ensuring that no one except the owner can see what is there on the screen.
## Proposed System:
![img1](https://github.com/polaiee/DataSecurity_FacialRecognition/blob/main/DataSecurityFaceRecog_images/image1.png)

**Face Detection:** it has the objective of finding the faces (location and size) in an image and probably extract them to be used by the face recognition algorithm.<br />
**Face Recognition:** with the facial images already extracted, cropped, resized and usually converted to grayscale, the face recognition algorithm is responsible for finding characteristics which best describe the image.<br />

### Proposed System Workflow: 
![img2](https://github.com/polaiee/DataSecurity_FacialRecognition/blob/main/DataSecurityFaceRecog_images/image2.png)
## Development Tools
### Hardware
 Operating System : Windows, Linux <br />
 GPU : NVidia <br />
 CPU : 8GB, 64 GB Hard disk <br />
 Base Configurations processor : i3,i5 <br />
### Software
 Programming Languages: Python <br />
 Packages: Computer Vision, CV2, OS, Numpy, Pyoutogui, datetime, PIL <br />
 IDE: VS CODE
## Implmentation
**Verification or authentication of a facial image:** it basically compares the input facial image with the facial image related to the user which is requiring the authentication. It is basically a 1x1 comparison. <br />
**Identification or facial recognition:** it basically compares the input facial image with all facial images from a dataset with the aim to find the user that matches that face. It is basically a 1xN comparison. <br />
## Algorithm
**LBPH (Local Binary Pattern Histogram)** is a Face-Recognition algorithm it is used to recognize the face of a person. It is known for its performance and how it is able to recognize the face of a person from both front face and side face.
### Steps: 
1. Parameters
2. Training the Algorithm
3. Applying the LBP operation
4. Extracting the Histograms
5. Performing the face recognition

#### Steps involved in this algorithm are as follows:
a) Dataset Creation
b) Face Acquisition
c) Feature Extraction
d) Classification

![img3](https://github.com/polaiee/DataSecurity_FacialRecognition/blob/main/DataSecurityFaceRecog_images/image3.png)

### Parameters initialized:<br />
Radius: the radius is used to build the circular local binary pattern and represents the radius around the central pixel. It is usually set to 1. <br />
Neighbors: the number of sample points to build the circular local binary pattern. The more sample points you include, the higher the computational cost. It is usually set to 8. <br />
Grid X: the number of cells in the horizontal direction. The more cells, the finer the grid, the higher the dimensionality of the resulting feature vector. It is usually set to 8. <br />
Grid Y: the number of cells in the vertical direction. The more cells, the finer the grid, the higher the dimensionality of the resulting feature vector. It is usually set to 8. <br />

## Process
![img4](https://github.com/polaiee/DataSecurity_FacialRecognition/blob/main/DataSecurityFaceRecog_images/image4.png)

### Creation of Data Sets
![img4](https://github.com/polaiee/DataSecurity_FacialRecognition/blob/main/DataSecurityFaceRecog_images/image6.png)
## Implementation
Using the captured images in the initial dataset creation the model  is trained. After the training a YML file is created. A YML file is a text document that contains data formatted using YAML (YAML Ain't Markup Language), a human-readable data format used for data serialization. It is used for reading and writing data independent of a specific programming language. Because YAML syntax is language-agnostic, YML files can be incorporated into programs written in most popular programming languages, including C/C++, Ruby, Python, Java, Perl, C#, PHP, and others.

![image4](https://github.com/polaiee/DataSecurity_FacialRecognition/blob/main/DataSecurityFaceRecog_images/image5.png)
