# AWS Cloud Devops Capstone Project

[![ky0men](https://circleci.com/gh/ky0men/uda-capstone.svg?style=svg)](https://github.com/ky0men/uda-capstone)

## _Introduction_

In this project you will apply the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program. These include:

- Working in AWS
- Using Circle CI to implement Continuous Integration and Continuous Deployment
- Building pipelines
- Working with CloudFormation to deploy clusters
- Building Kubernetes clusters
- Building Docker containers in pipelines

## _Application_

My application is a simple webpage based on python script using flask to render.

## _Kubernetes Cluster_

I used AWS CloudFormation to deploy the Kubernetes Cluster.
| File | Description |
| ------ | ------ |
| .circleci/files/network.yml | To create resources such as VPC, Internet Gateway, Subnet, Route Table, and Security Group |
| .circleci/files/eks.yml | Creates an EKS (Elastic Kubernetes Service) cluster with a specific version and configuration. It also creates an IAM role and instance profile for the EKS service to use|
| .circleci/files/node-group.yml | It defines an instance profile and IAM role for EC2 instances to join the node group, an EKS security group to allow traffic to and from the node group|

## _Check the script's code with pylint and Hadolint_

Output when lint failed
![Alt text]()

Ouput when lint success
![Alt text]()

## _CircleCi - CI/CD Pipelines_

![Alt text]()

## _Deployed Instances_

![Alt text]()

## _Deployment is successful output_

![Alt text]()

## _Access the application_

![Alt text]()
