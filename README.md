In this cloudformation stack deployment there are two steps to follow.

1. Setup an AWS four(4) stage CI/CD pipeline with manual approval in each steps.
2.  Writing a template for an architecture using few AWS services.
  
First step we have to build a CI/CD pipeline using cloudformation template. For this I have used AWS services such as AWS pipeline, codecommit, codebuild, codedeply. From below diagram we can understand how these each services are integrated each other.

![](images/ReGov Images.png)


