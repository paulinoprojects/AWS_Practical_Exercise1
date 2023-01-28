# AWS - Host a static website for free

## Design
- In this exercise, we are going to host a static website on AWS utilizing security and engineering best practices and industry standards.
- The objective and endstate is to supplement my resume and cover letter, and to encourage/assist others to follow the walkthrough.
- The next sections are the overview and walkthrough used to build the site. 
<br>
Note: This walkthrough assumes that you own a registered domain name.
</br>

## Overview of resources
- S3 Bucket, to store/host your static website and files:  https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html
- Route 53, to map a domain name to your bucket: https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html
- Cloudfront, to securely/efficently deliver your content to viewers: https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html
- Web Design HTML, free templates avaliable (this will require you to understand HTML code and syntax:  https://html.com/resources/free-html-templates/

## Workflow
1. Select a template and make adjustments to your code to fit your portfolio requirements.
2. Create/Configure an Amazon S3 bucket to store your website files. 
3. Enable static website hosting on the S3 bucket by setting the index document.
5. Use the AWS CLI or the S3 Management Console to upload your website files to the S3 bucket.
6. Create a CloudFront distribution and associate it with your S3 bucket to provide a global, low-latency, and high-throughput content delivery.
7. Update your domain name's DNS settings to point to the CloudFront distribution.

<br>
NOTE: You will be charged for the usage of Cloudfront and S3 but the free tier will cover most of the small static websites. You can check the pricing for S3 and Cloudfront on the AWS website.
</br>