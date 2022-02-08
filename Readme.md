# Image and Text Classification
This project is developed in Keras + OpenCV + NLTK to build some classifier models on the dataset images and their caption.

## Dataset
The dataset includes two `train` and `test` directories each contain `images` and `sentences` subdirectories for image and text classification, respectively.

You can get the dataset from [here](https://www.kaggle.com/mohsenm95/image-and-caption-classification).

## Environment
- Python: 3.7.12
- Tensorflow: 2.7.0
- Scikit-learn: 1.0.2
- Numpy: 1.19.5
- Pandas: 1.3.5
- Opencv-python: 4.1.2.30
- Opencv-contrib-python: 4.1.2.30
- NLTK: 3.2.5
- Tensorflow-hub: 0.12.0


## Future Works

* Image Classification:
    1. Improve data augmentation.
    2. Evaluate the model on other metrics(confusion matrix, F1-score, etc.)
    3. Visualize the model(for better interpretation). Read this[ repo](https://github.com/alexlenail/NN-SVG) and this[ link](https://end-to-end-machine-learning.teachable.com/p/neural-network-visualization). 
* Text Classification:
    1. Apply data augmentation technique(Read this[ survey](https://arxiv.org/abs/2110.01852)) on the dataset.
    2. Evaluate the model on other metrics(confusion matrix, F1-score, etc.)
    3. Visualize the model(for better interpretation). Read this[ repo](https://github.com/alexlenail/NN-SVG) and this[ link](https://end-to-end-machine-learning.teachable.com/p/neural-network-visualization).
* You will be given a caption as input, and you will be asked to find 10 images in the database whose captions are closer to the given caption. (Select images from the entire database, regardless of the input label). Then use the genetic algorithm and find a coefficient for each image so that by combining 10 images with these coefficients, the resulting image belongs to the category of input caption. You can use [variational autoencoder](https://theailearner.com/2018/11/10/variational-autoencoders/) for combining images. [This](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73) and [this](https://arxiv.org/abs/1312.6114) can be helful.


## Contributing
Fixes and improvements are more than welcome, so raise an issue or send a PR!