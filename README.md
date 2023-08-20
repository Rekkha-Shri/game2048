Game - 2048 app

![image](https://github.com/Rekkha-Shri/game2048/assets/136299028/05e1f39d-008e-42df-974c-88def184951b)

AWS DevOps Project

This application is deployed on EKS (Amazon Elastic Kubernetes Service) cluster which manages the control plane and its components, so for worker node we have used Fargate which is defined to run containers. 

Using Ingress, Ingress Controller the application is accessible by end-users. The ingress controller called as Application Load Balancer(ALB) controller watches the ingress resource and will create the Application Load Balancer(ALB). Through ALB request will comes to ingress, ingress routes the traffic to service(either ClusterIp or NodePort, ingress supports both type) and service allows the request into the cluster(Pod). 

``Prerequisites:``

kubectl – A command line tool for working with Kubernetes clusters.

eksctl – A command line tool for working with EKS clusters that automates many individual tasks.

AWS CLI – A command line tool for working with AWS services, including Amazon EKS. After installing the AWS CLI, configure it with access key & secret key.
