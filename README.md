# Boto3


Boto are a range of dolphines found, and native to the Amzon of south america.  Amzon plc use the name for their python 
API framework that provides a programmatic application interface (API) to Amazon cloud services.  The python API 
provides the Software development kit (SDK) to enable access to all the Amazon services available to users. 
The current (2020) version of Boto is 3, and is now stable recommendation for general python SDK use.
The table below outlines both the Amazon, and AWS services which the python BOTO SDK provides API.

[BOTO3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/s3-examples.html)



| **Amazon Services API Ref**                                   | **AWS Services**                    |
|-------------------------------------------------------|:---------------------------------:|
|[Amazon Textract](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html)                                        |  AWS Certificate Manager                                |
|[Amazon Transcribe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html)                                      |  AWS Cloud Development Kit (AWS CDK)
|[Amazon Translate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html)                                      |  AWS CodeCommit
|[Amazon SNS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html)                                            |  AWS Config
|[Amazon SQS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sqs.html)                                             |  AWS DeepLens
|[Amazon Simple Email Service]()                            |  AWS IoT Greengrass
|[Amazon Pinpoint Email API](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html)                            |  ``AWS Identity and Access Management``
|[Amazon Pinpoint SMS and Voice API](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sms-voice.html)                      |  AWS IoT
|[Amazon Pinpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html)                                      |  AWS IoT Things Graph
|[Amazon Polly](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html)                                         |  AWS Key Management Service
|[Amazon Relational Database Service]()                     |  AWS Lambda
|[Amazon Redshift](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift.html)                                        |  AWS Secrets Manager
|[Amazon Rekognition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html)                                     |  AWS Step Functions
|[``Amazon S3``](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html)                                          |  AWS Security Token Service
|[Amazon Kinesis Data Analytics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html)                          |  AWS Support
|[Amazon Kinesis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis.html)                                         |
|[Amazon Kinesis Data Analytics for Java Applications]()    |
|[Amazon Inspector](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html)                                       |
|[Amazon GuardDuty](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html)                                       |
|[Amazon DynamoDB](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html)                                        |
|[Amazon EC2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html)                                             |
|[Amazon Elastic Container Service](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html)                       |
|[Amazon Elastic Kubernetes Service]()                      |
|[Amazon Elastic Transcoder](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html)                              |
|[Amazon EMR](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr.html)                                             |
|[``Amazon S3 Glacier``](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html)                                  |
|[Amazon Comprehend Medical](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html)                              |
|[Amazon CloudFront](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html)                                      |
|[``Amazon CloudWatch``](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html)                                  |
|[Amazon API Gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigateway.html)                                     |

It can be used side-by-side with Boto in the same project, so it is easy to start using
Boto3 in your existing projects as well as new projects. Going forward, API updates and all new

##### feature work will be focused on Boto3.

## Feature

#### Installing boto3

```shell
pip install boto3

```

##### Installing AWS CLI version 2 - Commands for Linux install
```shell

curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

```
##### Installing AWS CLI version 2 - Commands for MacOS install

```shell

curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-macos.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

```


git tag <tagname>

## Continuous monitoring


## Infrastructure management approach
Infrastructure as a code (IaC) is an infrastructure management approach that makes continuous delivery and DevOps possible.

## Access Key
Your credentials can be passed into the methods that create connections. Alternatively, boto will check for the existence of the following environment variables to ascertain your credentials:

AWS_ACCESS_KEY_ID - Your AWS Access Key ID

AWS_SECRET_ACCESS_KEY - Your AWS Secret Access Key

Credentials and other boto-related settings can also be stored in a boto config file. See this for details.

### DevOps


##### DevOps Ecosystem:

![alt text](https://blog.testlodge.com/wp-content/uploads/2018/07/qa-in-devops.png "DevOps Ecosystem")

#### jmespath

#### Planning

Git
Jira
Confluence

#### Development


#### Testing

#### Deployment

#### Release



#### Monitoring

Nagios
Splunk
Slack
New Relic
Datadog
Wireshark