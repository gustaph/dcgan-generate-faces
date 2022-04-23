### Table of Contents

1. [Project Overview](#overview)
2. [Installation](#installation)
3. [Instructions](#instructions)
4. [Dataset](#dataset)
5. [Acknowledgment](#acknowledgment)

## Project Overview <a name="overview"></a>

The objective of this project is to define and train a *Deep Convolutional Generative Adversarial Network* (DCGAN) on a dataset of faces to generate new images of faces that look as realistic as possible.

Some sample results is show bellow.
![image](https://user-images.githubusercontent.com/54601061/164916283-6a67d652-9cac-4ffe-8b9d-7644a8178596.png)

## Installation <a name="installation"></a>

For development, the following dependencies were used:

- torch
- pickle
- numpy
- matplotlib

## Instructions <a name="instructions"></a>

1. Clone the repository and navigate to the downloaded folder.
	```	
	git clone https://github.com/gustaph/dcgan-generate-faces.git
	```
2. Download the dataset included below in the [Dataset section](#dataset) and put the zip file on the ```processed_caleba_small/``` folder.
3. Open the notebook and follow the rules.
	```
	jupyter notebook dlnd_face_generation.ipynb
	```
## Dataset <a name="dataset"></a>

The dataset was taken from [**Large-scale CelebFaces Attributes (CelebA) Dataset**](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). Additional information and license are available on the website.

## Acknowledgment <a name="acknowledgment"></a>

Must give credit to [**Udacity**](https://www.udacity.com).
