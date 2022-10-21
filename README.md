# Sapir Final Project - Summer 2022

Congratulations! After a lot of hard work in the DevOps, you've landed a job as DevOps Engineer for a
Software Start-Up company located in NY ,USA

You can using the following aws user for doing this project:
| Account ID | 777203705741 |
| ---------- | ------------ |
| Username   | project      |
| Password   | u1[HzmmPvHKfPlW |
| Access key ID | AKIA3J5HTM6GTWZUP4XW |
| Secret access key | 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 |


## Part 1️⃣ - Terraform (30 %)

As a Principal DevOps Engineer , you required to:
1. Create Dev Environment using IaC (Terraform) including:
 - New VPC (name it: {yourname}-dev-vpc) with connection to the internet
 - New Subnet ( {yourname}-k8s-subnet ) with 20 available IPv4 addresses

2. Run the code with the provided aws account and save:
`main.tf`
`main.tfstate`
files to a new github repo
  
3. Destroy all resources

## Part 2️⃣ - kubernetes (70 %)

Introduction:
Kubernetes coordinates a highly available cluster of computers that are connected to work as a single unit. The abstractions in Kubernetes allow you to deploy containerized applications to a cluster without tying them specifically to individual machines. To make use of this new model of deployment, applications need to be packaged in a way that decouples them from individual hosts: they need to be containerized. Containerized applications are more flexible and available than in past deployment models, where applications were installed directly onto specific machines as packages deeply integrated into the host. Kubernetes automates the distribution and scheduling of application containers across a cluster in a more efficient way. Kubernetes is an open-source platform and is production-ready.


1. Create ubuntu EC2 t2.micro instance ( {yourname}-k8s )
2. Connect to the instance using ssh , then install and setup: docker+kubectl+minikube
3. Create a k8s cluster using Minikube - `Take *Screenshot1* showing the result`
4. Deploying the App: gcr.io/google-samples/kubernetes-bootcamp:v1 
5. Test the app using kubectl Proxy `Take *Screenshot2* showing the result`
6. Scale up the app from 1 pod to 3 `Take *Screenshot3* showing the result`
7. Scale down the app from 3 pod to 2 `Take *Screenshot4* showing the result`
8. Save screenshots to the same github repo you have created in *part 1 














## 📧 For Contact:

email: `fadi@analiza-college.co.il`

discord: `Fadi#5225`


# Good luck!




