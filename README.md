# A-Diagnostic-Assistant
A Diagnostic Assistant is implemented which has two features. One is Anterior Cruciate Ligament (ACL) tear detection and another is cell nuclei segmentation. Used Convolutional Neural Networks to implement these features. These Networks analyse the input medical images and give outputs (tear or no tear for ACL detector and Mask of cell nuclei for cell nuclei segmentation) accordingly. Various Models and deep learning  techniques are implemented to achieve good accuracy.

Models implemented in PyTorch library of Python. Setup a Python environment in VSCode along with PyTorch installed to run the files.

# ACL Tear Detection
Here two datasets are used

KneeMRI Dataset: https://www.kaggle.com/datasets/sohaibanwaar1203/kneemridataset

MRNet Dataset: https://www.kaggle.com/datasets/cjinny/mrnet-v1/data

Download and input the path to these datasets accordingly in the code of the files.

Run the Extraction file on these datasets to extract the data after which all files can be run on the extracted data.

# Cell Nuclei Segmentation
Dataset: https://www.kaggle.com/competitions/data-science-bowl-2018/data

Download and input the path to these datasets accordingly in the code of the files after which all files can be run.
