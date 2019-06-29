# aws-sample-linux

Install AWS CLI

```pip3 install awscli --upgrade --user```

Get AWS Credentials - stored into  pip install requests --user

   ```git clone https://github.com/do-team/aws-dbg-saml```
   
Check credentials

```
[dave@localhost-dave ~]$ ls -1 .aws/
config
credentials
```

```
[dave@localhost-dave ~]$ more .aws/config 
[default]
region = eu-central-1
```


Install Python dependencies

```
 pip install requests --user

 pip install boto3 --user
 
 pip install bs4 --user

 pip install configobj --user

 pip install pytz --user
 ```
 
 
 Test AWS CLI
 
 Run  ```aws configure```
 
 Get instance description
 ```aws ec2 describe-instances --instance-ids SOME_ID```
