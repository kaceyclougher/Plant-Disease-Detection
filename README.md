# Plant Disease Detection using Deep Learning
### Author: Kacey Clougher

The advent of agriculture is often regarded as the pivotal moment in the establishment of human civilization. Agriculture is generally believed to have begun around 10,000 to 12,000 years ago during the Neolithic Revolution. This period marked a significant transition from hunter-gatherer lifestyles to settled agricultural communities, leading to the cultivation of plants and the domestication of animals. Despite the considerable progress made over the millennia (insert actual number of years since civilization began), enabling us to sustain a global population numbering in the billions, the foremost challenge confronting crop productivity remains the prevalence of plant diseases.

Exposure to diseases is a common occurrence in plants, influenced by factors like fertilizers, cultural practices, and environmental conditions. These diseases can adversely impact agricultural yield, consequently affecting the associated economy. Implementing techniques or methods to proactively address this issue and provide early warnings before plants succumb to infections would empower farmers to cultivate crops or plants more effectively, enhancing both qualitative and quantitative outcomes. Therefore, the detection of diseases in plants holds significant importance in the realm of agriculture.

Within this repository, you will find a comprehensive analysis that classifies pictures of leaves into two categories: healthy and diseased.

![pexels-tim-mossholder-974314](https://github.com/kaceyclougher/Plant-Disease-Detection/assets/137820049/995f0847-2437-4132-9f85-b0de6158b0eb)

## Repository Structure
* Data Split & Preprocess Notebook
* Final Model Notebook
* README.md: High-level README for reviewers of this project
* Streamlit App
* Technical Presentation

## Approach
Convolutional Neural Network (CNN) methodologies were employed to create an AI approach for detecting diseases in plants through leaf images. The neural network model or architecture was formulated using the Keras API and implemented using Python in conjunction with TensorFlow.

## Dataset and Preprocessing
Cornell University offers a collection of 50,000 meticulously curated images depicting both healthy and infected leaves of crop plants on the PlantVillage online platform. This study introduces and details both the dataset and the platform, titled ["An open access repository of images on plant health to enable the development of mobile disease diagnostics."](https://arxiv.org/abs/1511.08060). These data mark the initiation of an ongoing crowdsourcing initiative aimed at leveraging computer vision techniques to address the challenge of crop yield losses caused by infectious diseases. It was promotoed with a [plant disease detection competition] (https://www.aicrowd.com/challenges/plantvillage-disease-classification-challengez). 

The ImageDataGenerator was utilized to enhance our dataset by introducing various data transformations, including scaling, rotation, flipping, zooming, and shifting. Furthermore, a rescale factor of 1.0/255 was applied to normalize the data, and all images were resized to dimensions of 256x256. These transformations produced altered versions of the original images, effectively expanding our training data. Given the imbalance in our dataset, data augmentation proved beneficial for our moderately sized collection of 55,000 images.

## Key Tools
* Python
* Google Colaboratory
* TensorFlow
* Keras
* Matplotlib
* Numpy

## Modeling



## Reproducing the Experiment


## Presentation and Resources
