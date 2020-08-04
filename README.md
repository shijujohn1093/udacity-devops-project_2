"# aws_cloudformation" 


# Here we are considring folder name is the name of stach batch file will pick main.yml as the cloud formation script and parma.json is the parameter file

# To create stack use create.bat 
> create.bat network-stack-1

#  To update stach use update.bat
> update.bat network-stack-1


# For Udacity Project 2 tutroial we  here we need to run two stack as follow

> create.bat network-stack-1
> create.bat resource-stack-2

# Load balancer url for project 2

http://resou-WebAp-1S7TURTB3MZ2J-1588741839.us-west-2.elb.amazonaws.com