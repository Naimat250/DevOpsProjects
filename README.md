# Welcome to the AWS S3 Static Website Hosting Project
This README provides a quick guide to set up and deploy your website, taking advantage of the powerful and scalable AWS S3 infrastructure. Simple instructions for a seamless static website hosting experience.
Here are the steps for hosting a static website on AWS S3:
1: Create an AWS Account:
  -Sign up for an AWS account if you don't have one.
2: Access AWS S3 Console:
  -Log in to the AWS Management Console.
  -Navigate to the S3 service.
3:Create a New S3 Bucket:
  -Click on "Create Bucket" and follow the prompts.
  -Choose a unique name for your bucket(e.g., mnaimats3).
4:Configure Bucket for Static Website Hosting:
  -In the bucket properties, select "Static website hosting."
  -Specify the index document (e.g., index.html) and error document (e.g., error.html).
5:Upload Your Website Files:
  -Upload your static website files to the S3 bucket.
  -Ensure that the main page is named according to your specified index document.
6:Set Bucket Permissions:
  -Adjust bucket permissions to allow public access if necessary.
  -Configure the bucket policy to grant read permissions.
7:Enable Static Website Hosting:
  -Save the configuration changes.
  -Verify the provided endpoint URL for your static website.
8:Configure Domain (Optional):
  -If using a custom domain, set up a Route 53 hosted zone or update DNS records.
9:Test Your Website:
  -Open the provided endpoint URL or custom domain to verify that your static website is accessible.
10:Optimize for Performance (Optional):
  -Consider enabling CloudFront for content delivery and caching.
