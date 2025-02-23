## **AWS HOSTED RESUME WEBSITE <br> (CLOUD RESUME CHALLENGE)** <samp><img src="frontend/images/cloud1.ico" width="24" height="22" border="10"/></samp>


Check it out here: [ahmedharrisdevops.com](https://ahmedharrisdevops.com) 


## **Overview**
This project is my resume written in HTML and hosted in AWS. Inspired by the [Cloud Resume Challenge](https://cloudresumechallenge.dev/docs/the-challenge/aws/). The challenge was a great way for me to get hands on experience configuring and deploying cloud infrastructure, designing CI/CD pipelines, & delivering and monitoring applications.



## **Technologies/Tools used**
* Cloud: AWS, Route 53, CloudFront, S3, Lamba, DynamoDB, CloudWatch
* IaC: AWS CloudFormation
* Version Control: Git
* CI/CD: GitHub Actions
* Languages: Python, JavaScript, HTML, CSS 



## **Architecture** 
* Route 53 manages custom domains, routing traffic through CloudFront distribution.
* Website stored in S3, with CloudFront CDN providing HTTPS, global caching, and low-latency delivery.
* API Gateway triggers Python Lambda function, retrieving and incrementing visitor count in DynamoDB.
* GitHub Actions frontend CI/CD pipeline automatically deploys changes to HTML, CSS, and images into S3 bucket. Then refreshes CloudFront caches.
* GitHub Actions backend CI/CD pipeline automatically deploys Python Lamba Function & DynamoDB to AWS.
* Utilized CloudWatch monitoring and logging to track service performance.



## **Planned Features**
* Terraform IaC
* Add Unit & End to End Testing 
* Add Profile Page
* Enhance Website Design

