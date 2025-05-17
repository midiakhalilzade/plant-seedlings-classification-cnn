# Plant Seedlings Classification with CNN

This project is a simple convolutional neural network (CNN) built using PyTorch to classify images of plant seedlings into 12 categories.

The task was part of a deep learning course, where a model previously used for classifying cats and dogs was adapted to a new dataset of plant images.
---

## Dataset

The dataset includes 12 plant species:
Black-grass
Charlock
Cleavers
Common Chickweed
Common wheat
Fat Hen
Loose Silky-bent
Maize
Scentless Mayweed
Shepherds Purse
Small-flowered Cranesbill
Sugar beet


🔗 Dataset source: [Plant Seedlings Classification on Kaggle](https://www.kaggle.com/c/plant-seedlings-classification)

All input images were resized to **224×224 pixels** for consistency.  
**This resizing was done intentionally** to match the input size requirements of ResNet-based models, which may be used in future versions of this project.  
**20% of the training data** was set aside for validation.
---

## Model

A simple CNN model was used consisting of two convolutional layers followed by a fully connected output layer.

> **Note**: The model structure is based on an exercise provided by the course instructor for binary image classification (cats vs. dogs), adapted here to a multi-class plant classification task.
---

## Results

- **Training Accuracy**: 96%  
- **Validation Accuracy**: 66%
---

## Future Improvements

- Add data augmentation techniques
- Try pretrained models like ResNet
---

## Author

Project by [midia khalilzade](https://github.com/midiakhalilzade)    
Created as part of a deep learning course exercise.
