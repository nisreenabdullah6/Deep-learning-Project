## Deep learning classification model to detect the driver state :
> In this project our task was to get a dataset to build an deep learning classification model. We chose to analyze a dataset obtained from a kaggle that collects an images for the driver state.


> -  We divided the data into three clases(Holding phone,safe driver,distracted driver). 
> - Train datatset: Found 19624 images belonging to 3 classes.
> - Validation dataset: Found 2800 images belonging to 3 classes.
> - Test dataset: Found 2800 images belonging to 3 classes.
> - Three classes :{'distracted': 0, 'holding_phone': 1, 'safe': 2}
> -  Then, we rescale the images size to 150 x 150.
> -  Then, we build  DL baseline model.

## Data Collection :

>**We chose the State Farm Distracted Driver Detection dataset for this project:**
>- The dataset was obtained from  this website https://www.kaggle.com/c/state-farm-distracted-driver-detection/data 
>- the dataset contains 10 classes each class contains around 2000 images .



## EDA graph:

>This graph shows the number of images for each class in the training set.

<img width="450" alt="Screen Shot 2021-11-15 at 7 19 52 PM" src="https://github.com/nisreenabdullah6/Deep-learning-Project/blob/main/EDA%20Graph_2.png">

##  DL baseline model
> My baseline model was is DL model that contains 1 hidden layer of 32 units and the accuracy on train set for 1 and val set for 0.9986, but there still has gaps to improve for accuracy and loss.

<img width="450" alt="Screen Shot 2021-11-15 at 7 19 52 PM" src="https://github.com/nisreenabdullah6/Deep-learning-Project/blob/main/acc_loos%20graph_2.png">



## Future work:


1.to improve accuracy scores
- > use CNN and do hyperparameters tuning 
- > use Transfer Learning (VGG16).
- > tasting our best Model.





```python

```
