# Udacity-Cloud-Devops-Engineer-Prj1
Host a Static Website to S3

In This Project We will show you how to host a simple static website in AWS S3 Bucket

Preparation:
- An AWS Account
- Source Code of Website you want to host.
- S3 Bucket
- CloudFront for Distribution your website

Action Steps:
1. Create the Bucket with the unique name format my-<12 digits of your AWS Account>-bucket
2. Upload your code folder into the S3 Bucket one by one. Including directories: css, vendor, images and file: index.html and README
3. Configure IAM Policy and then setting up Host Static Website for your Bucket
4. Create the Distribution in CloudFront service and then access to the website after creating it.

In my project you can Access with two ways
- CloudFront Endpoint URL is: https://d1upt6ijahfzql.cloudfront.net/
- Website Endpoint URL: http://my-839757017467-bucket.s3-website-us-east-1.amazonaws.com/
