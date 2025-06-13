# AWS-cli Installation on Ubuntu server

# Additional Notes:
Permissions: Ensure you have sudo privileges to install the CLI system-wide.

# Configuration: After installation, configure the AWS CLI with your credentials using:
aws configure

# This will prompt you for your AWS Access Key ID, Secret Access Key, region, and output format.

# Cleanup: You can remove the downloaded files to save space:
rm -rf awscliv2.zip aws

# Troubleshooting: If aws --version doesn't work, ensure /usr/local/bin is in your $PATH. You can check with echo $PATH and add it temporarily using export PATH=$PATH:/usr/local/bin.
