# Image Classification with Vision Transformer
A project to fine tune the Vision Transformer on a dataset for a classification task.

## Project Setup

Run ```data.py``` to download the dataset in the correct sub-directory. ```image-classification.ipynb``` contains the code for:
1. Loading dataset and feeding it to the models
2. Performing data augmentation, as is necessary to train a transformer-based model on a small dataset.
3. Visualizing the data augmentation.
3. Loading the models from PyTorch 
4. Running the Training Loop, and saving the model to disk
5. Loading the models from disk and making predictions on the test dataset.


## References

Project originally done for CSE 144: Applied Machine Learning at UCSC during Winter 2024.
The class was taught by [Prof. Cihang Xie](https://cihangxie.github.io/).

