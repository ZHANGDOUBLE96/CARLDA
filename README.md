# User Guide

- The **codes** folder stores the code files required to run the experiment, where **API_Reco.py** is the main file, **Model.py** is the code file for building the model, which can be used to modify the model structure, **losses.py** defines the loss function used by the model, and **utils.py** defines some auxiliary functions, such as parameters of the main file (such as batch size, running epochs, etc.), and training functions.
- The **data** folder stores the data set used. The folder **train** is the training dataset, the folder **valid** is the validation dataset, the folder **test** is the test dataset, the folder **aug** is the data set constructed through data augmentation, and the folder **few** is the small-scale dataset built by RQ4. **Dataset_Finegrained.json** corresponds to the dataset **Dataset_Finegrained** in the paper, **Data_Common.json** corresponds to the dataset **Dataset_Common** in the paper, and **Dataset_Morphological.json** corresponds to the dataset **Dataset_Morphological** in the paper.   
- The running environment of the experiment is ubuntu 20.04, RTX 4090, and the running command is ``python API_Reco.py``. **Requirements.txt** lists the package list used for experimental environment configuration.

