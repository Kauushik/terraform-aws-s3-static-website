# Terraform AWS S3 Static Website

## Project Overview

This project demonstrates how to deploy a static website on AWS S3 using Terraform (Infrastructure as Code).

The entire infrastructure, including the S3 bucket, website configuration, public access settings, and HTML file upload, is managed through Terraform.

## Technologies Used

* Terraform
* AWS S3
* HTML
* Infrastructure as Code (IaC)

## Resources Created

* S3 Bucket
* Static Website Hosting Configuration
* Public Access Configuration
* Bucket Policy
* Website Endpoint Output

## Project Files

* `main.tf` – Creates and configures AWS resources
* `variables.tf` – Stores variables
* `outputs.tf` – Displays website endpoint
* `index.html` – Static website content
* `.gitignore` – Excludes Terraform state files

## Deployment Steps

1. terraform init
2. terraform plan
3. terraform apply
4. Access the website using the generated endpoint
5. terraform destroy

## Screenshots

Project screenshots are available in the `screenshots` folder.

## Outcome

Successfully deployed a static website on AWS S3 using Terraform and verified public access through the website endpoint.
