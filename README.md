# Overview
The kidney classification overview is included in the [wiki](https://github.com/aiman3/Kidney-Disease-Classification/wiki) !

# Installation

To run this project locally, follow these steps:
Clone this repository to your local machine:
```bash
git clone https://github.com/your_username/kidney-disease-classification.git
```
Navigate to the project directory:
```bash
cd kidney-disease-classification
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```

# Run
Run the mode you desire in src folder (ResNet50 or VGG-19)
* Data will download via code in notebook
* Data will preprocess from prewritten code

# Train 
* Run Training mode on notebook 

# Other notes
The required dependencies is in requirements.txt but all required dependencies is included in .ipynb files.


# Usage
After installing the necessary dependencies, you can train and evaluate the ResNet50 model and vgg19 model by running .ipynb files.
when run the .ipynb file, you can download dataset too. In src folder, resnet50, vgg19 models are included. 


# Results
this is training and validation result of vgg19. 
![image](https://github.com/aiman3/Kidney-Disease-Classification/assets/167260360/6079f495-c868-4860-899c-cd90f2df1446)
this is training and validation result of resnet50. 
![image](https://github.com/aiman3/Kidney-Disease-Classification/assets/167260360/15f192b5-856c-42d1-b5db-05f88d329a65)
this is the test result of vgg19.
![image](https://github.com/aiman3/Kidney-Disease-Classification/assets/167260360/599684e9-d480-4df4-aeee-653570a00424)
this is the test result of resnet50.
![image](https://github.com/aiman3/Kidney-Disease-Classification/assets/167260360/de237fd9-3cac-4e77-a441-9a9fef969eca)


# Resources
dataset has 12,446 images. Normal folder has 5077 images, Cyst folder has 3709 images. tumor folder has 2283 images, and stond folder has 5077 images.

dataset link: 
https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone
![image](https://github.com/aiman3/Kidney-Disease-Classification/assets/167260360/5ebdd2cc-599d-41d0-95ca-62c166335937)

# Future Work
This includes the implementation of INCEPTION-RESNET​, ALEXNET, and ZFNET. 

INCEPTION-RESNET​ gives clear empirical evidence that training with residual connections accelerates the training of Inception networks significantly​ and presents several new streamlined architectures for both residual and non-residual Inception networks.

ALEXNET is a classic convolutional neural network architecture​ and consists of convolutions, max pooling and dense layers as the basic building blocks

ZFNET's design was motivated by visualizing intermediate feature layers and the operation of the classifier​ and compared to AlexNet, the filter sizes are reduced and the stride of the convolutions are reduced