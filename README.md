# Detecting-COVID-19-From-Chest-X-Ray-Images-using-CNN

# Cov CNN Web Application

## About
A Django-based Web Application to detect the presence of [COVID-19](https://en.wikipedia.org/wiki/COVID-19) in Chest X-Ray Images. The Deep Learning models are trained on a publicly available dataset of ~2500 Chest X-ray images labelled as either COVID-19 or non-COVID. For better comparison purposes, three different architectures were used which include, Xception, ResNet50 and VGG16. The models were trained separately on the dataset and the weights were later loaded onto the Web app to detect the presence of COVID-19

## Demo 
<p align="center">
  <img src="/Demo/demo.gif" alt="animated" />
</p>

## Model Performance

### ResNet50 

- **Model Architecture**
<br>
<p align="center">
<img src ="https://user-images.githubusercontent.com/53687927/118810680-c8b25600-b8c9-11eb-9d98-35baa3f3f42e.png"></p>

- **Loss Curves**
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/53687927/118811264-6c036b00-b8ca-11eb-8105-c9c8673e3d6c.png"></p>

- **Confusion Matrix Obtained**
<br>
<p align="center">
<img src ="https://user-images.githubusercontent.com/53687927/118810998-1cbd3a80-b8ca-11eb-80c7-78a6ecbd2665.png"></p>

### VGG16
- **Model Architecture**
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/53687927/118811078-3494be80-b8ca-11eb-9948-7e06064030c3.png"></p>

- **Loss Curves**
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/53687927/118811293-74f43c80-b8ca-11eb-9de3-d9380c082aea.png"></p>

- **Confusion Matrix Obtained**
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/53687927/118811129-42e2da80-b8ca-11eb-9ed3-6c0126180241.png"></p>


## Xception

- **Model Architecture**
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/53687927/118811164-4fffc980-b8ca-11eb-8462-6dba7559e9ea.png"></p>

- **Loss Curves**
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/53687927/118811317-7d4c7780-b8ca-11eb-87b3-c3d96955522a.png"></p>

- **Confusion Matrix Obtained**
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/53687927/118811202-5aba5e80-b8ca-11eb-82f5-2f199909453d.png"></p>


Reference: **https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset**
           **https://www.geeksforgeeks.org/detecting-covid-19-from-chest-x-ray-images-using-cnn/**
