# Static Website Project

## Description
This is a simple static website hosted on AWS S3. The website displays a welcome message along with a short introduction and an image.

## Features
- Displays a welcome message.
- Includes a short intro message.
- Shows an image.

## Setup Instructions
1. **Create an S3 Bucket**:
   - Go to the S3 service in the AWS Management Console.
   - Create a new bucket and enable static website hosting.
   - Upload the `index.html` and `error.html` files.

2. **Enable Public Access**:
   - Set the bucket policy to allow public read access.
   - Disable block public access settings.

3. **Access the Website**:
   - Use the provided S3 website endpoint to access your site.

## Usage
Visit the website at: http://static-website-bucket-egi1.s3-website.eu-north-1.amazonaws.com/

## Technologies Used
- AWS S3
- HTML
- CSS
