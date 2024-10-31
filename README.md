# Final_Project-DevOps_Bootcamp

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Under the scope of [DevOps Engineer Bootcamp](https://www.patika.dev/bootcamp/protein-devops-engineer-bootcamp), which is sponsored by [Protein Tech](https://protein.tech) and organized by [Patika.dev](https://www.patika.dev), this project has been prepared by me as the Final Project. 

</br>

</br>

You will be able to find all necessary documents, which you may possibly need to evaluate the project. If you particularly landed on this page to evaluate this project, you can [click here](#satellite-evaluation-guide) to jump the section which I've prepared as evaluation guide.

</br>

# :link: Content

1. [Technologies](#computer-technologies)
2. [About](#clipboard-about)
3. [Tasks](#warning-tasks)
	- [Bonus Part](#star-bonus)
4. [Evaluation Guide](#satellite-evaluation-guide)
5. [Contact](#mailbox-contact)

</br></br>

# :clipboard: About

The endeavour of this project is to complete all given tasks. Tasks are mentioned in [Tasks](#tasks) section. In order to accomplish that; I've prepared a very simple and primitive React App. 


It is one page static web page. I accomodate the project in GitLab repository and I use GitLab CI/CD Pipeline to automatize my deployment. I deploy my React App onto AWS ECS Fargate cluster. I provision my AWS resources via Terraform. Besides of that, in case of it wants to be used, there is available Kubernetes manifest files to deploy the app manually to a Kubernetes cluster.

</br>

# :warning: Tasks

Tasks are mainly like that:
- Create a basic React.js app.
- Create a Dockerfile for your app. Try to form an image with the smallest possible size.
- Design and write a GitLab CI/CD pipeline.
- Use **Terraform** to provision the infrastructure.
- Application should be running on ECS Fargate
- Make sure to use the ideal VPC and security group settings.
- Application load balancer must be configured in front of the service.
- Write the required core Kubernetes manifest files for Kubernetes deployment.

## :star: Bonus

- Configure auto-scaling onto your Fargate instance. Scale-up when CPU is above %50 and scale-down when CPU is below %20.
- Create the proper Cloudwatch dashboards and metrics for monitoring the performance of the application.
- Draw your AWS architecture, explain the connections and relations between your configured services.
- Instead of using GitLab's shared runners, you can configure your own runner.
- Write a script that sends a notification by E-mail if the disk usage exceeds 90% in an operating system using any Linux distribution.


# :satellite: Evaluation Guide

Here I leave neccessary links for each assigned task. Simply by clicking them you can quickly jump into relevant section.

1. [Create a basic React.js app](./react-app/)
2. [Create a Dockerfile for your app](./react-app/README.md#dockerize)
3. [Design and write a GitLab CI/CD pipeline](./react-app/README.md#cicd-pipeline)
4. [Use Terraform to provision the infrastructure](./react-app/README.md#terraform)
5. [Application should be running on ECS Fargate](./react-app/README.md#ecs)
6. [Make sure to use the ideal VPC and security group settings](./react-app/README.md#vpc)
7. [Application load balancer must be configured in front of the service](./react-app/README.md#alb)
8. [Feel free to include or use any other AWS service(i.e. S3)](./react-app/README.md#s3)
9. [Write the required core manifest files to deploy the application to Kubernetes](./kubernetes/README.md#content)
10. [Describe your strategy and choices about Kubernetes](./kubernetes/README.md#strategy)

**BONUS**

11. [Configure auto-scaling onto your Fargate instance. Scale-up when CPU is above %50 and scale-down when CPU is below %20](./react-app/README.md#asgtf)
12. [Create the proper Cloudwatch dashboards and metrics for monitoring the performance of the application](./react-app/README.md#dashboardtf)
13. [Draw your AWS architecture, explain the connections and relations between your configured services](./react-app/README.md#aws-architecture)
14. [Instead of using GitLab's shared runners, you can configure your own runner. If you do so, please share the runner's config.toml and clarify the implementation process](./bonus_part/gitlab-cicd-runner/README.md)
15. [Write a script that sends a notification by E-mail if the disk usage exceeds 90% in an operating system using any Linux distribution](./bonus_part/alert_script/README.md)

</br>

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)
* [PayPal.me](https://www.paypal.com/paypalme/nholuongut)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟