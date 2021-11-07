# t-SNE
An implementation of the t-SNE paper for our SMAI course project in Monsoon'21

## Team members
1. Kunal Jain (2019111037)
2. Samay Kothari (2019113017)
3. Aaditya Sharma (2019113009)
4. Adwait Raste (2019111027)

The paper is available [here](./tsne.pdf)

## Problem Statement
Visualization of high-dimensional data is an important problem in many different domains, and deals with data of widely varying dimensionality. The goal of visualizing such data is to give a basic understanding of the distributions and possible properties of the dataset we are dealing with in a format that is easily comprehendable by humans.

A lot of techniques have been developed for this task like UMAP, pixel-based techniques, etc. However, most of the earlier techniques focus on simply displaying the high dimensional data in two dimensions without taking into consideration the interpretability of the generated visualisation to the human. This creates a need for a method to represent the data in an interpretable fashion.

This creates the problem of preserving as much of the significant structure of the high dimensional data as possible in the low dimensional visualisation.

![tSNE vs UMAP](./images/tsne_vs_umap.png)
## Goals and Approach
Implement t-SNE
## Dataset
We plan to test our implementation on a number of datasets to ensure generalisability of the technique. We will use the following datasets: 
1. MNIST : This consists of 60,000 grayscale images of handwritten digits. Each image is 28 X 28 = 784 pixels (dimensions).
2. Olivertti faces : This is dataset of 400 images created with 40 indivisuals who change their expressions in the images along with small variations in viewpoint. Each image is 92 X 112 = 10,304 pixes (dimensions) labelled with their identity.
3. COIL-20 : There are 1440 images of 20 objects taken from 72 space orientation (equally spaced). Each image is 32 X 32 = 1,024 pixels (dimensions).
4. Animals10 : There are about 55000 images of animals from 10 classes. Each image is 64 X 64 = 4096 pixels (dimensions)

## Expected Deliverables
t-SNE
## Rough timeline
1. 7 November - 12 November : Paper review
2. 12 November - 17 November : Testing standard implementations of the methond using pre-built libraries on given dataset, test on newer datasets
3. 17 November - 1 December : Implementation of t-SNE and testing with existing implementations

The above timeline is approximate and may change as the project progresses.

## Work distribution
1. Kunal Jain - paper review
2. Samay Kothari - paper review
3. Aaditya Sharma - paper review
4. Adwait Raste - paper review

The above will be updated accordingly as the project progresses.