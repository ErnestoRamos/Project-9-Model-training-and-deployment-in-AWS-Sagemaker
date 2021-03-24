# Project Overview:

1. download data from a url
2. load the data into sagemaker and split into train, val and test
3. Upload train, val and test into S3
4. Load Xgboost algo from container and fit using train and val set via s3
5. Deploy the model within sagemaker 
6. Make prediction on test set 
7. Show results in confusion matrix format
