# demoPipeline



ssh -i ~/.ssh/your-key.pem ec2-user@<your-ec2-public-ip>





sudo yum install -y httpd
sudo systemctl start httpd
sudo systemctl enable httpd
sudo chown ec2-user /var/www/html
