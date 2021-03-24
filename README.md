# Project Overview:

1. download data from a url
2. load the data into sagemaker and split into train, val and test
3. Upload train, val and test into S3
4. Load Xgboost algo from container and fit using train and val set via s3
5. Deploy the model to create an endpoint
6. Use endpoint to make prediction on test set 
7. Show results in confusion matrix format

Note that with the now endpoint created, we can create an API using AWS Lambda and API Gateway 
https://aws.amazon.com/blogs/machine-learning/call-an-amazon-sagemaker-model-endpoint-using-amazon-api-gateway-and-aws-lambda/
