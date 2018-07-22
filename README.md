# aws-nodejs-sdk-ec2-instance

This project uses AWS SDK for JavaScript in Node.js to perform some basic operations on AWS EC2 instances.

# Some of the operations performed are:

    1. Create an EC2 instance
    2. Wait for instance to reach a "Running" state
    3. Delete the EC2 instance
    4. Wait for the instance to be "Terminated"
    
# Pre-requisites:

    1. Node should be installed
    2. AWS account should be setup with necessary permissions
    
# Steps to run:

    1. Navigate to config file and add personal access details
    2. Install aws-sdk dependencies
        - npm install
    3. Run the script
        - npm run test
