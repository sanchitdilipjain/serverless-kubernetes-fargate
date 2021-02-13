## Serverless Kubernetes: AWS EKS on Fargate

**Introduction**

Amazon is investing more effort into their serverless stack and this functionality will allow us to run Kubernetes in a “serverless” mode. I am really thrilled about being able to run Kubernetes pods in Fargate as this minimizes the overhead to run Kubernetes applications and there is zero need to run any EC2 worker nodes.

This article will cover the following topics:

- Deploy EKS on AWS Fargate
- Deploy Application Load Balancer on AWS Fargate

**AWS Fargate**
<br>AWS Fargate allows us to build and deploy containerized applications without worrying about underlying infra and it also reduces a lot of the overhead involved with deploying applications. 

**AWS Elastic Kubernetes Service (EKS)**
<br>EKS is Amazon’s fully managed Kubernetes Service that allow to run Kubernetes on AWS without managing the control plane and it also reduces a lot of the overhead involved with having to manage and run the control plane.

**How to setup an EKS cluster on Fargate**

***Prerequisites***
<br>The following tools we will be leverage for this demo:
- <a href="https://docs.aws.amazon.com/eks/latest/userguide/eksctl.html">eksctl</a>: Official CLI to create a new EKS cluster.
- <a href="https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html">kubectl</a>: Kubernetes uses a command line utility called kubectl for communicating with the cluster API server.

***Setting up***

- Deploy EKS on AWS Fargate

- Deploy Application Load Balancer on AWS Fargate
