# Shellscript_aws.sh
AWS Resource Usage Tracker

Overview


This shell script is designed to report the AWS resource usage for the current AWS account. It retrieves information about the following AWS resources:
S3 buckets
EC2 instances
Lambda functions


IAM users
The script generates separate output files for each resource, containing relevant details.


Author
Author: Srikanth
Date: 11 sept 2023
Version: v1



Prerequisites
Before running the script, ensure you have the following requirements met:


AWS CLI is installed and configured with valid credentials for the AWS account you want to track.


Execution
To execute the script, run the following command:


./aws_resource_tracker.sh
