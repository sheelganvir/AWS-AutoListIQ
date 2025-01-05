# AWS-AutoListIQ 📊

**AWS-AutoListIQ** is an automation script designed to streamline the process of listing all resources in an AWS account. This tool supports various AWS services, enabling users to quickly get an inventory of their cloud resources. 

## Features ⚙️

- Automates resource listing across key AWS services:
  - **EC2**
  - **RDS**
  - **S3**
  - **CloudFront**
  - **VPC**
  - **IAM**
  - **Route53**
  - **CloudWatch**
  - **CloudFormation**
  - **Lambda**
  - **SNS**
  - **SQS**
  - **DynamoDB**
  - **EBS**
  
- Prompt-based user input for region and service selection.
- Supports multiple regions for flexibility.

## Installation 🛠️

### Pre-requisites

1. **AWS CLI** should be installed and configured. Follow the [AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html).
   
2. Configure AWS CLI by running:
   ```bash
   aws configure

3. Clone the repository:
   ```bash
   git clone https://github.com/sheelganvir/AWS-AutoListIQ.git

4. Navigate to the project directory:
   ```bash
   cd AWS-AutoListIQ

## Usage 📝
To execute the script, use the following syntax:
   ```bash
   ./aws_resource_list.sh <aws_region> <aws_service>
   ```
## Script Explanation 📘
- Inputs: Accepts AWS region and service as inputs.
- AWS CLI Verification: Checks if AWS CLI is installed and configured.
- Resources Listing: Lists resources based on the specified service and region.
## Troubleshooting ❓
- If the AWS CLI is not installed, the script will notify you to install it.
- If an invalid service is provided, the script will display an error message and exit.

## Contributing 🤝
Feel free to fork this repository and contribute improvements. Create an issue if you encounter bugs or have suggestions for new features.

## 📚 License
This project is open-source and available under the MIT License.

