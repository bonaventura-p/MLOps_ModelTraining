# RACe-VR

Please open a SageMaker instance on AWS and clone this git folder.

Then open the get_data notebook to pull the experimental data from WISDM. Please ensure that the S3 bucket name is correct, you have access to it.

Running the ModelTrainDeploy notebook will do everything for you, provided that you have access to the S3 buckets. Otherwise, replace the S3 bucket path with one you have access to.

Finally, you can upload your own test data (assuming they have a suitable structure) and push it to the endpoint to obtain the predicted results. In misc, you can find an example test file from WISDM.


![alt text](https://github.com/bonaventura-p/race-vr/tree/master/images/race-vr.png)
