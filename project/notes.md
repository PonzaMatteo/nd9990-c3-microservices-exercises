# Project Execution

Writing my own notes during the execution of the project. 


## Requirements

- usql: https://github.com/xo/usql
- node
- ionic: npm install -g @ionic/cli
- docker
- aws: create user with admin rights
- kubectl


### Create an user with admin rights

- Go to IAM page and create an user with name `Admin-Udacity`
- Grant Programmatic Access
- Grant `AdministratorAccess`
- Download credentials as CSV   
- Configure the user with `aws configure` then enter the credentials and specify the default region `ap-southeast-1`

Can run some command like the following to verify that the setup is succesfull.

```sh
aws iam get-user
or 
aws s3 ls
```

