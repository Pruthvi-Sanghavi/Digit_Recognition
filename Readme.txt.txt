## Install Dependencies
pip install jupyter notebook


## Setup Instructions (for windows)
- Unzip the compressed folder
- Open command prompt 
- Navigate to the code directory
```
cd pruthvi_proj2/pruthvi_P2/code/
```
- Run the following.
```
pip install -r requirements.txt
```

## Datasets
- MNIST Dataset
- Monkey Dataset(https://www.kaggle.com/slothkong/10-monkey-species/home)

#### For Monkey Dataset
- Download the dataset, extract the files
```
cd code/monkey_classifier
mkdir datasets
```

- Copy the ```training```, ```validation``` folders and ```monkey_labels.txt``` from the downloaded folder and paste it to datasets folder.

## Training the dataset
- Type the following in command prompt 
- For Digit Recognition using CNN
```
cd code/digit_cnn
ipython notebook digitCNN.ipynb
```
- For Digit Recognition using SVM
```
cd code/digitSVM
ipython notebook digitLSVM.ipynb
OR
ipython notebook digitKPSVMSVM.ipynb
OR
ipython notebook digitKRSVM.ipynb
```
- For Monkey Classification using CNN
```
cd code/monkey_classifier
ipython notebook monkeyCNN.ipynb
```


- For Monkey Classification using Transfer Learning
```
cd code/monkey_classifier
ipython notebook monkeyTL.ipynb
```
## Trained models
```
cd code/monkey_classifier
ipython notebook monkeyTL_trained.ipynb
```
```
cd code/digit_cnn
ipython notebook digit_CNN_trained.ipynb
```