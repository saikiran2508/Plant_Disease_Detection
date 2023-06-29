
# Detection of Plant Disease

<div align="center">

<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://img.shields.io/badge/Built%20by-developers%20%3C%2F%3E-0059b3"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=yellow"></a>
<a href="https://github.com/kashish-ag/"><img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg?v=103"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://img.shields.io/badge/PR's%3F-Welcomed-brightgreen.svg?v=103"></a>

<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/watchers"><img src="https://img.shields.io/github/watchers/kashish-ag/Detection-of-Plant-Disease?style=flat"></a> 
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/graphs/contributors"><img src="https://img.shields.io/github/contributors/kashish-ag/Detection-of-Plant-Disease?color=brightgreen"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/stargazers"><img src="https://img.shields.io/github/stars/kashish-ag/Detection-of-Plant-Disease?color=0059b3"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/network/members"><img src="https://img.shields.io/github/forks/kashish-ag/Detection-of-Plant-Disease?color=yellow"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/issues"><img src="https://img.shields.io/github/issues/kashish-ag/Detection-of-Plant-Disease?color=0059b3"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/issues?q=is%3Aissue+is%3Aclosed"><img src="https://img.shields.io/github/issues-closed-raw/kashish-ag/Detection-of-Plant-Disease?color=yellow"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/pulls"><img src="https://img.shields.io/github/issues-pr/kashish-ag/Detection-of-Plant-Disease?color=brightgreen"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/pulls?q=is%3Apr+is%3Aclosed"><img src="https://img.shields.io/github/issues-pr-closed-raw/kashish-ag/Detection-of-Plant-Disease?color=0059b3"></a> 
</div>
<p align=center>
<img src="https://user-images.githubusercontent.com/74819092/124498690-63afb280-ddda-11eb-8a50-10ec7d46db44.png" hieght=400, width=400>
</p>

## Introduction

Getting affected by a disease is very common in plants due to various factors such as fertilizers, cultural practices followed, environmental conditions, etc. These diseases hurt agricultural yield and eventually the economy based on it. 

Any technique or method to overcome this problem and getting a warning before the plants are infected would aid farmers to efficiently cultivate crops or plants, both qualitatively and quantitatively. Thus, disease detection in plants plays a very important role in agriculture.

## The PlantVillage Dataset

We use a publicly available and quite famous, the PlantVillage Dataset. The dataset was published by crowdAI during the ["PlantVillage Disease Classification Challenge"](https://www.crowdai.org/challenges/plantvillage-disease-classification-challenge). 

The dataset consists of about **54,305 images** of plant leaves collected under controlled environmental conditions. The plant images span the following **14 species**:

> **Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato.**

The dataset contains a total of **38 classes** of plant disease and **1** class of background images listed below:
|                     |                      |                        |                          | 
| :---:               |    :----:            |          :---:         |         :---:            |  
| Apple Scab          | Apple Black Rot      | Apple Cedar Rust       | Apple Healthy            |
| Blueberry Healthy   | Cherry Healthy       | Cherry Powdery Mildew  | Corn Northern Leaf Blight|
|Corn Gray Leaf Spot  |Corn Common Rust      |Corn healthy            | Grape Black Rot          |     
|Grape Black Measles  | Grape Leaf Blight    | Grape Healthy          | Bell Pepper Healthy      |
| Orange Huanglongbing|Peach Bacterial Spot  | Peach Healthy          |Bell Pepper Bacterial Spot|
| Potato Early Blight | Potato Healthy       | Potato Late Blight     |Raspberry Healthy         |
| Soybean Healthy     | Squash Powdery Mildew| Strawberry Healthy     | Strawberry Leaf Scorch   |
|Tomato Bacterial Spot| Tomato Early Blight  | Tomato Late Blight     |Tomato Leaf Mold          |
|Tomato Septoria Leaf Spot| Tomato Two Spotted Spider Mite | Tomato Target Spot |Tomato Mosaic Virus |
|Tomato Yellow Leaf Curl Virus | Tomato Healthy      |    |    |


Due to the limited computational power, it is difficult to train the classification model locally on a majority of normal machines. Therefore, we use the processing power offered by Google Colab notebook as it connects us to a free TPU instance quickly and effortlessly.
