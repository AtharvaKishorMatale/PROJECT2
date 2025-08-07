# Project 2: VPC Flow Logs to S3 using IAM Role

## Project Title
**Configure VPC Flow Logs and Store Logs in S3 Using IAM Role**

## Objective
Create a secure and efficient system to capture and store VPC traffic logs using AWS Flow Logs and deliver them to an S3 bucket for:

- **Network troubleshooting**
- **Security analysis**
- **Regulatory auditing**

## Technology Stack
- **Networking:** Amazon VPC, AWS Flow Logs
- **Storage:** Amazon S3
- **Access Control:** AWS IAM

## Implementation Highlights

### Secure Log Storage
- S3 bucket created with versioning enabled
- Bucket policy to securely store flow logs

### Least Privilege Access
- IAM role with minimal permissions to allow VPC Flow Logs to write to S3

### Automated Data Capture
- VPC Flow Logs configured at the VPC level
- All network traffic streamed to the S3 bucket

### Data Verification
- Verified log delivery in S3
