# Skin Cancer detection using Deeplearning pretrained Models
## Welcome
The main goal of this Capstone Project is to make a model for detecting skin cancer and set up the system for using it. I'll be using two pre-trained Keras applications, Xception and EfficientNet, without the top layers, to create three different models. Because of limited time and the limited free computing power available in Colab, I didn't try making more models or systems and I was not able to experiment with the done models as much as I would like. After checking, the best results I got a 0.71 accuracy on the validation dataset. This is far from the standards for detecting skin cancer in the industry, so, the model needs more work to usable in the medical field and only has a educative perspective. I will work beyond this course to make a model that works addecually. 

This project was devided into the following parts:
1. Why Skin Cancer Detection?
2. Dataset Employed
3. Models Trained

## Why Skin Cancer Detection?
Skin cancer emerges as one of the rapidly proliferating diseases worldwide. It involves the uncontrolled development of abnormal skin cells. Detecting and diagnosing the disease early are crucial steps in identifying potential cancer therapies
[1].
The present challenge associated with manual identification performed by skilled medical professionals is its susceptibility to variation based on experience in the field. Even in the case of experts, there is a potential for mislabeling. For instance, the accuracy in diagnosing basal cell carcinoma (BCC), indicated by the higher positive predictive value (PPV), stands at 72.7% [2].
The application of AI models has proven to be an invaluable tool for skin cancer identification. This technology enables individuals with smartphones to achieve accuracies comparable to or surpassing those of trained experts [3].

[1] Detection of Skin Cancer Based on Skin Lesion Images Using Deep Learning - Healthcare (Basel). 2022 Jul; 10(7): 1183. - 10.3390/healthcare10071183
[2] Accuracy of clinical diagnosis of skin lesions -  Br J Dermatol. 2008 Sep;159(3):661-8 - 10.1111/j.1365-2133.2008.08715.x 
[3] Assessment of Accuracy of an Artificial Intelligence Algorithm to Detect Melanoma in Images of Skin Lesions -  JAMA Netw Open. 2019;2(10):e1913436 - 10.1001/jamanetworkopen.2019.13436 


## Dataset:
For the present work the Dataset from The International Skin Imaging Collaboration​ (ISIC) 2016 and 2017 challenge datasets were used:
* [Challenge 2016: Training](https://api.isic-archive.com/collections/74/)
* 

https://www.isic-archive.com/
