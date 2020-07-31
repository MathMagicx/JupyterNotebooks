# Recommender for similar images based on Resnet18

This is a basic item-item recommender system implementation. Based on the resnet18 implementation from PyTorch it creates feature vectors from the input images, compares it to the other images and sorts for each image a similarity list. Eventually, the result is visualized for a tiny test set that is provided within the repository.

The overall theory is explained here: https://towardsdatascience.com/effortlessly-recommending-similar-images-b65aff6aabfb

The implementation from this repository is described in another article on Medium https://towardsdatascience.com/recommending-similar-images-using-pytorch-da019282770c?source=your_stories_page---------------------------

The version of the notebook server used for the notebook is 5.0.0, running on:
Python 3.6.3 |Anaconda custom (64-bit)| (default, Oct 15 2017, 03:27:45) [MSC v.1900 64 bit (AMD64)]

Folder originalImages contains 21 images of different class that will be grouped when running the notebook.

With new Python versions you might have problems running PyTorch
Needed libaries are listed in requirements.txt