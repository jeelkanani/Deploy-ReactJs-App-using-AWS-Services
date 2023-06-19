# Deploy-ReactJs-App-Using-AWS-Services

I have deployed and Monitering ReactJs applications using the following AWS services and Popular Tools Like,<br><br>
👉 Amazon VPC<br>
👉 CloudFormation<br>
👉 AWS EKS ( Elastic K8s Service )<br>
👉 IAM Role<br>
👉 Amazon EC2<br>
👉 Amazon AutoScaling<br>
👉 LoadBalancer<br>
👉 Promethes<br>
👉 Grafana<br>
<br>

##  Pre-Requisites
* AWS Account with admin previliges<br>
* Instance to manage/access EKS cluster using kubectl (K8S-Client-VM)<br>
* AWS CLI Access to use kubectl utilty<br>


## Architecture of the Project <br>
![image](https://github.com/jeelkanani/Deploy-ReactJs-App-using-AWS-Services/assets/80504844/90bbc853-787e-4cfd-be8c-10ef807ea8ed)<br>

## A Step-by-Step Guide

####  1) Create VPC Using Cloud Formation 
* cloud formation is an infrastructure as a code service using that I have created VPC and that IAC mentions in the above abc.txt file.<br>
* So Here First Create Cloudeformation stack that name is EKSVPC cloudformation and add IAC code inside it.<br>
<br>![image](https://github.com/jeelkanani/Deploy-ReactJs-App-using-AWS-Services/assets/80504844/b6ac4291-3fce-4632-9745-b975dbd87962)<br>

* when successfully create completed after then we will see VPC create successfully.

<br>![image](https://github.com/jeelkanani/Deploy-ReactJs-App-using-AWS-Services/assets/80504844/0c7b9395-e07a-4cff-8c39-bce08467416d)<br>











