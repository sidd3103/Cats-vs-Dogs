# Cats-vs-Dogs
This project is my first neural network. It tackles a binary classification problem in computer vision. It determines whether an image is of a cat or a dog. Training is done on 2000 images while validation and test sets each contain 1000 images. Images are taken from https://www.kaggle.com/c/dogs-vs-cats/data?select=train.zip

Since the dataset is so small compared to the original dataset of 20000 images, issues like overfitting came up. I also used data augmentation to tackle overfitting and increase the accuracy. I also used the VGG16 model trained on the ImageNet dataset for my model and used feature extraction and fine-tuning to make the model better.

Note: Be sure to enable GPU in Google Colab, if it's not enabled. Go to Runtime -> Change Runtime Type -> Hardware Accelerator and select GPU
