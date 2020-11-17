# Mini-Project_Scene-Analyzer

## ML Model
The actual images dataset is too large to upload. It was downloaded from this link: https://www.kaggle.com/puneet6060/intel-image-classification/version/2

I renamed the folders seg_pred to pred, seg_train to train and seg_test to test.

For the ML model, first 50 images from each category were taken for training in 'train' folder and first 10 images from each category for testing from 'test' folder.

The resolution was shrunken down to 48 * 48 for quicker processing. 

I've also included the preprocessed dataset (Flattened image data array) in case you want to run the model based on my selected datas.

Every model has their own parameters list defind so, performing GridSearch will be very easy in case you want to try on a differernt set of data.

In my tests, the Kernel SVM performed the best (Parameters are in the jupytr notebook)


## Deep Learning Model

This model uses all the images at full resolution for better accuracy.

I've also included the saved model in case you don't want to retrain the model on your system.
