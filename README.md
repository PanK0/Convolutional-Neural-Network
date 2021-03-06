# Convolutional Neural Network
Machine Learning homework about the classification of images regarding objects in a home environment. 

In this homework we were invited to provide a solution for the classification of images regarding objects in a home environment. To solve the problem I took into account the given exercise about **Ensebles of Convolutional Neural Networks**, adapting that to the problem and explaining my decisions for the proposed solution.

See the full Report of the homework [HERE](https://github.com/PanK0/Convolutional-Neural-Network/blob/main/Report/report_hw2.pdf).

## Important notes to know
- The code in file *cnn.py* [here](https://github.com/PanK0/Convolutional-Neural-Network/tree/main/src) is the same as in the **Colab Notebook** available [here](https://github.com/PanK0/Convolutional-Neural-Network/tree/main/Colab%20Notebook).
- To train this Neural Network upload the [**Colab Notebook**](https://github.com/PanK0/Convolutional-Neural-Network/tree/main/Colab%20Notebook) on Google Colaboratory. 
- To use GPU in Colab, set `Edit / Notebook settings / Hardware accelerator` to **GPU**.

## The Dataset
- The Dataset is contained in the folder [Dataset](https://github.com/PanK0/Convolutional-Neural-Network/tree/main/Dataset) in two zipped files.
- The Dataset is already splitted into Train Set and Test Set. The only thing to do is to **unzip** the directories and then **upload** on your Google Drive (see below).
- You can modify the code to change the paths as you like.
- Each one of the two Train and Test directories contains eight subdirectories, where the images are stored.

## Upload the dataset in Google Drive
Follow these instructions if you don't want to modify the paths in the code.
- Create a directory in your Google Drive named *ML2021*.
- Create another directory into *ML2021* called *hw2*, such that the **absolute path** will be `/content/drive/MyDrive/ML2021/hw2/`.
- Put the unzipped folders *train150* and *test150* into the folder *hw2*. The final results should be to have two folders `/content/drive/MyDrive/ML2021/hw2/train150` and `/content/drive/MyDrive/ML2021/hw2/test150`.

## Original Homework Request
This homework aims at solving an image classification problem with objects typically available in a home environment. To this end, we will use the RoboCup@Home-Objects dataset that has been developed within the RoboCup@Home competition.

Each student will solve a personalized 8-classes classification problem (as a subset of the entire dataset), depending on his/her matricola code.

To generate your dataset, follow these steps:

1) Duplicate this Colab and put your matricola number in the piece of code below (replacing the ERROR string)

2) Run the code and take note of the 8 printed labels

3) Download the corresponding 8 ZIP files from this folder

https://drive.google.com/drive/folders/1dL4OZRPLahq6aSgWxk9efmFbfoy1Vp0I

4) Use images in these 8 ZIP files as dataset for your 8-classes image classification problem
