# Brain Tumor Analysis Project
This is the github repository for the final project. Our task was to identify brain tumor types via deep learning.

## How To Use / Runnables
### Obtain Data
Data was obtained from Kaggle, which is located [at this link.](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/data) Download and unzip.
### CoLab Usage
Each ipynb is intended to be used with Google CoLab in mind, but can be run locally. In order to run and achieve the results outlined in the presentation and paper, upload to the data to Google Drive and the ipynb to CoLab.

Also do note that if you wish to run the code, your must change the file paths in each notebook so that it reflects the filepath of your own Google Drive.

Each ipynb corresponds to a different model, but each all have the following features:
- Model dataloader
- Training a pretrained instance of that model
	- Loss over time graph
- Evaluation
	- Confusion matrix
	- ROC curves
	- TTA Evaluation
## Contributions
Minseo - resnet.ipynb

Jude - README.md, vit.ipynb

Mary - alexnet.ipynb