

# Clinical BCI Challenge WCCI-2020

This repository contains code and data related to CBCI Challenge-2020 organized by University of Essex. 

## Overview
In this competition, we are provided an EEG Dataset of 10 hemiparetic stroke patients having hand functional disability. The dataset consists of two classes which are left and right-hand grasp attempt movements. The participants in the competition are required to provide accurate and robust decoding of these movements, from the provided brain activity only. The automated decoding of these kinesthetic movements from brain signals is helpful for the development of robot-assisted therapies or interfaces for assistive technologies or rehabilitation. The decoding will be done in two ways: 1) one is within-subject classification where the training data from the same subject will be used to classify that subject’s test data, 2) another challenge will be to perform these decoding across subjects where the training data of the 8 out of 10 subjects will be used to predict the test data of the remaining 2 subjects.
 - [Dataset Link](https://github.com/5anirban9/Clinical-Brain-Computer-Interfaces-Challenge-WCCI-2020-Glasgow)
 - [Competition Website Link](https://sites.google.com/view/bci-comp-wcci/?fbclid=IwAR37WLQ_xNd5qsZvktZCT8XJerHhmVb_bU5HDu69CnO85DE3iF0fs57vQ6M)

## How to Run it?
The code is primarily written in Python in the form of Jupyter Notebook. In order to run, it you should have installed Python on your computer. The required packages are listed in requirements.txt file.  
You can view the code by opening the files at Github. Sometimes, Github have some issues in previewing Jupyter Notebooks so you may try again to 'Reload' or Just copy paste the url of the notebook and paste it in  [nbviewer](https://nbviewer.jupyter.org/)


## Results
![Within Subject Classification](https://drive.google.com/file/d/1RFX37wzsWSkA8NdZXbn7ce7-OGlFw8_Y/view?usp=sharing)

![Cross Subject Classification](https://drive.google.com/file/d/1Z01Mp7ZEI4mOw1meoUCN4ISLa4OjkZnN/view?usp=sharing)