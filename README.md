# AWS-Polly
This README provides a step-by-step guide on how to convert text into speech using Amazon Web Services (AWS) Polly in Python. Polly is an AWS service that allows you to generate lifelike speech from text. Here, we'll demonstrate how to use the AWS SDK for Python (Boto3) to interact with Polly and save the synthesized speech as an MP3 file.

# Prerequisite
Before running the script, make sure you have the following set up:

AWS Account: You'll need an AWS account with the necessary permissions to create S3 buckets.
Python: Ensure that you have Python installed on your system.
Boto3 Library: Install the Boto3 library using pip.

# Preview

https://github.com/neelay-16/AWS-Polly/assets/135517502/bd73eb64-faf2-4750-8ae8-e695c2685fa7


# Description

Create a Polly client by specifying the AWS region you want to use. Here we use the "ap-south-1" region.

![image](https://github.com/neelay-16/AWS-Polly/assets/135517502/9d04c3e2-648a-46db-945a-22ef45effb1c)


Use the Polly client to synthesize speech from the provided text. You can specify the voice and output format. In this case, we use the "Matthew" voice and request the output in MP3 format.

![image](https://github.com/neelay-16/AWS-Polly/assets/135517502/ab3bf163-2ad3-4685-9eca-3c37249d8030)


Save the synthesized speech to an MP3 file named 'output.mp3'

![image](https://github.com/neelay-16/AWS-Polly/assets/135517502/7f4f1632-be12-4726-abd6-b92a47f61447)

