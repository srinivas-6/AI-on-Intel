# AI-on-Intel
## AI from Data Center to the Edge - An optimized path using Intel Architecture

## Objective

Using Intel hardware and sofware portfolio for demonstarting the Data Science process. Hands on understanding of building a Deep Learning model and deploying to the Edge.


* Using the concept of Transfer Learning for Image classification problem
* Exploratory Data analysis on Vehicle Make and Model Recognition (VMMR) dataset
* Training three different frameworks (Inception V3, VGG and MobileNet) on Intel Dev cloud
* Obtaining the graph and weights of the trained networks
* Evaluation of the models and freezing the graphs obtained
* Deployment to the Edge using Intel OpenVINO Toolkit 

For Setting up the Environment on your workstation or on Intel AI Devcloud refer to 

## Exploratory Data Analysis on Vehicle Make and Model Recognition (VMMR) dataset
The project starts with [VMMR](http://vmmrdb.cecsresearch.org/), contains 9170 classes, identified 76 Car Manufacturers and 291,752 samples in total. The time scale of the dataset covers models manufactured between 1950-2016. VMMRdb dataset contains images that were taken by different users, different imaging devices, and multiple view angles, ensuring a wide range of variations to account for various scenarios that could be encountered in a real-life scenario.

Data Creation, Preprocessing and Data Augmentation see [here](Data_analysis)

## Training three different frameworks (Inception V3, VGG and MobileNet) on Intel Dev cloud
Training a model involves multiple steps, Choosing a framework (TensorFlow), Transfer Learning (InceptionV3, VGG16, MobileNet), Training the models and tune it for better performance, Hyper parameter tuning, Generate a frozen graph (a trained model) for inference on Edge.

Training and comparision of the performance & results see [here](training)

## Evaluation of the models
Interpreting the results of the training by analyzing the models with different metrics and graphs see [here](model_analysis)

* Confusion Matrix
* Classification Report
* Precision-Recall Plot
* ROC Plot

## Deployment to the Edge using Intel OpenVINO Toolkit
Inference on edge is real time evaluation of model subject to the contraints of power, latency and memory. Intel's OpenVINO toolkit optimizes pre-trained models for inference on intel processors.

For Deployment of the frozen model using OpenVINO Toolkit see [here](deployment)
## Resources

* Intel AI Academy 
https://software.intel.com/ai-academy

* Intel AI Student Kit
https://software.intel.com/ai-academy/students/kits/

* Intel AI DevCloud
https://software.intel.com/ai-academy/tools/devcloud

* Intel AI Academy Support Community
https://communities.intel.com/community/tech/intel-ai-academy
