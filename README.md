# AWS OTT Project 1: Video Hosting with EC2 + S3 + NGINX

This project demonstrates how to stream HLS video content by combining:
- AWS S3 for storing HLS `.m3u8` and `.ts` files
- EC2 (Amazon Linux) as a hosting server
- NGINX as a lightweight web server to deliver video content

## Key Steps:
1. Uploaded HLS files to an S3 bucket
2. Launched EC2 (Amazon Linux), installed NGINX
3. Configured EC2 IAM Role for S3 access
4. Pulled content from S3 to EC2 and hosted with NGINX

## Skills Used:
- AWS EC2, S3
- IAM Role & Policy setup
- NGINX setup & configuration
- AWS CLI usage
