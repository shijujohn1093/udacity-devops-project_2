"# aws_cloudformation" 


## Here we are considring folder name as the name of stack and batch file will pick main.yml inside folder as the cloudformation template and param.json is the parameter file

## To create stack use create.bat 
> create.bat network-stack-1

##  To update stach use update.bat
> update.bat network-stack-1


## For Udacity Project 2 tutroial we  here we need to run two stack as follow

> create.bat network-stack-1
> create.bat resource-stack-2

## Load balancer url for project 2

http://resou-webap-1590ba2a1y2bv-1747557991.us-west-2.elb.amazonaws.com/