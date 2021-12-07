# Seminar (I) 1101216 Brain tumor detection in MR image

###### tags: `Seminar`

[Brain tumor detection in MR image using superpixels, principal component analysis and template based K-means clustering algorithm - ScienceDirect (oclc.org)](https://www-sciencedirect-com.nutc.idm.oclc.org/science/article/pii/S2666827021000220)

Author: Md Khairul Islam, Md Shahin Ali, Md Sipon Miah, Md Mahbubur Rahman, Md Shahariar Alam, Mohammad Amzad Hossain
Source: Machine Learning with Applications
Impact factor: 6.954 (Expert Systems with Applications)

## New topic

- template-based K-means
- superpixels

## 1. Introduction

### 1.1. Motivation

Brain, the paramount significant and critical structural part of the human body that consists of 50–100 trillion neurons. It is also known as central part of human body.

To the best of our knowledge, it is too hard and complex to diagnose brain disease due to the existence of the skull around it (Gondal & Khan, 2013).

> 說明大腦的重要性和檢查大腦的麻煩處

a brain tumor is the result of uncontrolled growth of cells within the brain. “It causes cancer that may be the reason for death and accounts for around 13% of all deaths worldwide”.

Brain tumors are mainly two types such as benign and malignant. The tumors that do not contain cancerous cell and less harmful to human is called benign. Whereas the tumor that exists cancerous cell that is more harmful to humans is called malignant (Ali et al., 2021, Borole et al., 2015). 

> 說明腦腫瘤的危害和分類，看後面有沒有提到良性跟惡性造成的分類問題決定要不要拿掉。

MRI is a more popular non-invasive technique for detecting abnormalities of tissue composition. It is used rather than other medical imaging methods, offering the best contrast images of the brain and cancer tissues.

Brain tumor detection means recognizing the infected portion of the brain with the shape, size, position, and boundary of the tumor.

> 說明MRI棒棒還有腦腫瘤檢測的目標

Group pixels identical in color and other low-level properties are known as superpixels. 

The superpixels function is very useful in feature extracting that uses the simple linear iterative clustering (SLIC) algorithm.

Principal Component Analysis (PCA) is a technique that decreases the dimensionality of the dataset, enhances interpretability and minimizes data loss.

in the proposed scheme both superpixels and PCA are used to reduce complexity of image and execution time. 

> 介紹標題說到的兩個東西在幹嘛。

### 1.2. Contributions

> TK-means他說是他們提的
> superpixel跟PCA一起用他說他們提的
> 精度跟速度都比以前快

## 2. Related work

> 把以前用來找腦瘤的方法一個一個拿出來噴，看後面決定這邊要不要加

a large number of machine learning algorithm have been built up and used for the detection of brain tumor.

“However, these techniques had less accuracy and more time-consuming (i.e., non-automated)”.

## 3. Materials and methods

![](https://i.imgur.com/I3VVEmN.png)

### 3.1. Dataset

In this study, we first consider that the MRI scan images of given patients are with a default size of 256 × 256, either colorful or grayscale intensity images.

If it is a color image, a big matrix with numerical input values between 0 and 255 is used to measure the converted grayscale image, where 0 is black and 255 is white for illustrations.

To create our dataset, we have taken some critical images from [21] open access data, and some images are taken locally (Alam et al., 2019).

### 3.2. Preprocessing

In preprocessing, our aim is the enhancement of images that works well for the next step of the detection scheme.

There are two common types of filters namely mean filter and median filter are used to reduce noises from an image.

On one hand, the mean filter uses the mean values of all pixels instead of the central values of an image. On the other hand, the median filter uses the median values of all the pixels instead of the central values of an image.

> 太長上面這段可以刪

In our proposed scheme, we used a median filter for less computation complexity and better smoothing of images.

The median filter has two fundamental points of interest over the mean filter (Srivastava et al., 2009):

- It is a more powerful assessment than the mean. One unrepresentative pixel during a neighborhood will not affect the median significantly.
- Since the median is the value of one of the pixels within the neighborhood, it does not​ generate new ridiculous pixel values.

### 3.3. Feature extraction

#### 3.3.1. Features extraction using superpixels

#### 3.3.2. Features extraction using PCA

### 3.4. Segmentation and tumor detection

#### 3.4.1. Template based K-means clustering algorithm

#### 3.4.2. Morphological operation

## 4. Results and discussion

### 4.1. Inference and forecasting

### 4.2. System performance

## 5. Conclusions and future work

## Dark Theme CSS

{%hackmd theme-dark %}