# CI/CD Pipeline using Jenkins and AWS EC2

## Project Description
This project demonstrates a simple **CI/CD pipeline** that deploys a static website to an **AWS EC2 instance** using **Jenkins** and **Apache (httpd)**.

Any change made to `index.html` in GitHub can be deployed automatically to the EC2 server using Jenkins.

## Tools Used
=> Jenkins
=> GitHub
=> AWS EC2
=> Apache (httpd)
=> Linux
=>SSH & SCP

## How the Pipeline Works
1. Code is pushed to GitHub  
2. Jenkins pulls the latest code  
3. Jenkins copies the file to EC2 using SCP  
4. Apache serves the updated website  
## How to Run
=> Launch an EC2 instance
=>Install Apache (httpd)
=> Configure Jenkins
=> Run the Jenkins job to deploy the website

## Result
The website is deployed successfully and updates automatically whenever the source code changes.


## Author
Bhavitha Chowdhary
