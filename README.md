# deploy-mc24
Medical Center Deployment

## ssh connection
```ssh -i /Users/zagovorychev/aws/secret/mc24/Mc24Ubuntudemo.pem ubuntu@ec2-35-159-50-6.eu-central-1.compute.amazonaws.com```

## copy files to EC2
```scp -i Mc24Ubuntudemo.pem /Users/zagovorychev/www/sandbox/projects/mc24sandbox/composer.lock ubuntu@ec2-35-159-50-6.eu-central-1.compute.amazonaws.com:/home/ec2-user/downloads/mc24git/composer.lock```

