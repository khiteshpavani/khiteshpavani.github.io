README
*NOTE: The package contains a small sample test data set of 64 images which can be tested using the already trained model. In order to do the training the original data set can be downloaded from the Kaggle Site. In order to perform testing on a small sample data set, simply run "python test.py"

1) Download the NIH Chest X-ray Dataset from Kaggle into the data (presently empty) folder provided.
2) For running training Run "python train.py"
3) For running testing make sure the model ("my_saved_model.h5") is present in the folder and run "python test.py"
4)  For running the GUI Standalone the following files are required: 
    a)diagnose_xray
	b)True_Labels.csv
	c)weights.h5
	d)x_rays folder containing random x-rays
	
5) Considering the large dataset the parameters have been minimized in the files. The actual testing and training were done for complete dataset and also for longer epochs. Code from the following github repo was used for running some of the tests (https://github.com/brucechou1983/CheXNet-Keras).

*Use keraspreprocessing version 1.0.5 to avoid getting error in next function used.