AWS Project: Hosting a Static Website with S3
1. Project Overview
This project demonstrates how to host a static website using Amazon S3 (Simple Storage Service).  The goal is to display a simple, fast and cost-efficient website without needing a web server.

2. Objective
Learn how to create and configure an S3 bucket for website hosting.
Understand how to manage permissions using Bucket policies
Enable public access for website files securely
Test and verify that the website is publicly accessible

3. Tools and Services used
Amazon S3
IAM (Identity and Access Management)

4. What is an S3 bucket?
An Amazon S3 bucket is the fundamental storage container in Amazon Simple Storage Service (S3). It’s where all your data such as files, documents, images, videos, backups, and even static websites are stored in the cloud. You can think of it as the top-level directory or folder inside S3 that holds your data, but it comes with powerful management, security, and scalability features that go far beyond a normal folder on your computer.

5. Steps taken to complete the project
     a) Create an S3 bucket
          Open the AWS Management Console → S3 service.
          Click “Create bucket.”
          Choose a globally unique name (e.g., my-cafe-website).
          Select the region (in this case I selected a region closest to my location, Europe-Ireland).
          Uncheck “Block all public access.”
          Click Create bucket.
     b) Upload Website file
          Open the bucket → Upload the index.html, style.css, and any image files.
          Ensure the main file is named index.html (default entry point).
     c) Enable Static Website Hosting
          Go to Properties tab → scroll to Static website hosting.
          Click Edit → Enable it.
          Specify:  Index document: index.html
          Save changes.
          Copy the Bucket website endpoint — this will be the website’s URL.
     d) Set Bucket Policy for Public Access
          Go to Permissions
          Click Bucket policy
          Click Edit - replace the bucket name accordingly
     e)Test the Website
          Open your S3 Website Endpoint URL in the browser
          Static website is live!
6. Outcome
Successfully hosted and configured a fully functional static website on Amazon S3.
Gained practical experience with AWS permissions, bucket policies, and hosting setup.
Learned how to make cloud-based deployments simple and cost-effective.

