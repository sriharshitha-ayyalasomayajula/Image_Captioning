## Image Captioning using CNN and a Transformer 
Project Overview: 
The goal of this project is to generate captions for images using a combination of Convolutional Neural Networks (CNNs) and Transformers. 
Here, we define our own CNN model, Transformer encoder-decoder model which are used for image feature extraction and caption generation 
respectively. The model is then trained on the Flickr 8k dataset, which contains 8,000 images and captions, and the predictions are evaluated. 

Requirements:
The following libraries and packages are required to run the code: 
*  Python 3.x 
*  Tensor low 
*   NumPy
*   Matplotlib 

To install these packages in anaconda environment, use the following commands: Tensor low:
#create a conda environment and activate it
conda create --name tf python=3.9 
conda activate tf 
#Install tensor low pip install tensor low 
Numpy:
conda install -c anaconda numpy 
Matplotlib:
conda install -c conda-forge matplotlib 

Steps:
To get started, follow these steps: 
1.	Download the Filckr 8k dataset from this git repository (Link) or from kaggle. 
2.	Extract the iles to a local directory. 
3.	Clone my git repository, and run image_captioning.py on your local console. 
       python image_captioning.py 

Conclusion:
In this project, we defined a model with CNN for feature extraction and Transformer based encoder decoder model for caption generation 
and trained this model on Flickr 8k dataset. We see that the model gives reasonable captions after a few epochs. 
For future work, we can use a RNN for caption generation instead of a transformer or try a different model for accurate caption generation. 

