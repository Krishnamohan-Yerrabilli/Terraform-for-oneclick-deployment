# React.js Web Application on AWS

This project showcases how to deploy a React.js web application using AWS services and Terraform for infrastructure management. It automates the creation of key resources, ensuring a smooth and efficient deployment process.

## Key Features

- **Automated Deployment:** One-click deployment script using Terraform to set up AWS resources.
- **Infrastructure as Code:** Consistent and repeatable setups reduce errors.
- **Hosting Options:** Deploys the application on EC2 and S3 for flexibility.

## Getting Started

### Prerequisites

- **AWS Account:** Make sure you have an active AWS account.
- **Terraform Installed:** Follow [this guide](https://www.terraform.io/downloads.html) to install Terraform.

### Simple Setup Instructions

### Clone the repository:

      git clone https://github.com/Krishnamohan-Yerrabilli/Terraform-for-oneclick-deployment/edit/main/README.md 

#### 2) Initialize Terraform

      terraform init   

#### 3) Plan the infrastructure:

      terraform plan 

#### 4) Apply the changes:

   terraform apply   

#### Project Structure

    main.tf: Contains the Terraform configuration.
    package.json: Lists the project dependencies.
    src/: Contains the source code for the React app.

#### Contributing

Feel free to submit issues or pull requests. Contributions are welcome!
License

This project is licensed under the MIT License.
