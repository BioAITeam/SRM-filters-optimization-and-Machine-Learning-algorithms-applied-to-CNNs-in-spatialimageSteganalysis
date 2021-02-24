# Preprocessing stage Improving CNNs based on SRMoptimization for spatial image steganalysis
The main contribution from researchers in the image steganalysis field are new architectures that further improve the detection accuracy of steganographic images, usually a Convolutional Neural Network (CNN) combining feature extraction and classification in a single model. Nevertheless, preprocessing is one of the most important stages and has a direct impact on the overall performance of CNNs. This paper presents a modification on the preprocessing stage of existing CNNs, improving accuracy without major changes on the original architectures. Furthermore, it presents an evaluation of the performance of traditional machine learning models when using image features extracted using CNNs. These results indicate that certain modifications in the preprocessing stage of the classification process have a positive effect on the detection accuracy.
## Folders
- **CNNs Bifurcation** This folder contains the notebooks GBRAS-Net, Ye-Net, Xu-Net, Yedroudj-Net, VGG-16stego and VGG-19stego with a bifurcation for preprocessing of steganographic images. 
- **ML_ActivationMaps_Filters** In the notebook **paperGBRAS-Net_ML_Activation_Maps.ipynb**, features are obtained from GBRAS-Net bifurcation and steganographic image classification is performed based on machine learning methods. In the notebooks **paperGBRAS-Net_activation_maps_tp_tpn_fp_fn.ipynb** and **paperGBRAS-Net_filters_activation_maps.ipynb** are the algorithms to obtain the different activation maps shown in this research.


 
## Requirements
This repository requires the following libraries and frameworks:

- TensorFlow 
- scipy
- scikit-learn
- Datetime
- numPy 
- OpenCV 
- Yellowbrick
- Matplotlib
- Time
- random
- os
- scikit-image
- glob

This repository was developed in the Python3 (3.8) programming language.

## Package installation

if you don't use google colab, We highly recommend to use and install Python packages within an Anaconda enviroment. To create, execute the command below:
```
conda create --name Improving python=3.8
```
So, activate it
```
conda activate Improving
```
installed the framework
```
conda install -c anaconda keras-gpu==2.4.3
```
Now, install the libraries.
```
pip install opencv-python
conda install -c conda-forge matplotlib
conda install -c anaconda scipy
conda install -c jmcmurray os
conda install -c conda-forge time
conda install -c anaconda scikit-image
conda install -c anaconda scikit-learn
conda install -c trentonoliphant datetime
conda install -c districtdatalabs yellowbrick
```
## Execution
After installing all the Requirements, you must clone the repository using.
```
git clone https://github.com/BioAITeam/Preprocessing-stage-Improving-CNNs-based-on-SRMoptimization-for-spatial-image-steganalysis
.git
```
If you will use colab, upload the cloned folder to drive, Select the folder of your choice and run the notebook of your choice.

if you are going to use your computer, install:
```
conda install jupyter 
```
Enter the cloned folder, Select the folder of your choice and run the notebook of your choice.

## Note 
- Before running the notebook, please verify that the file paths are correct.
-  From the Notebook **paperGBRAS-Net_ML_Activation_Maps.ipynb** activation maps of the last three convolutions and the last Bach Normalization were obtained and generated as images, which enter different machine learning classifiers. The activation maps can be downloaded from the <a href="https://drive.google.com/drive/folders/1G5vdhW11_qKfVC6W8_pfJpstVkXUk1QQ?usp=sharing">link</a>.
## Databases


The data set used to reproduce the results can be downloaded from this <a href="https://drive.google.com/drive/folders/1G5vdhW11_qKfVC6W8_pfJpstVkXUk1QQ?usp=sharing">link</a>. Images taken from: <a href="http://agents.fel.cvut.cz/boss/index.php?mode=VIEW&tmpl=materials">BOSS competition</a> and <a href="http://bows2.ec-lille.fr/index.php?mode=VIEW&tmpl=index1">BOWS2</a>.
#### NPY
After accessing the link, enter the strategy folder 
#### PGM
After accessing the link, enter the GBRAS-Net folder 

