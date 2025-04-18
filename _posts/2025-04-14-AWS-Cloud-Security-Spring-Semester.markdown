In the Spring semester of 2025, I enrolled in a Cloud Security course that focused on designing and implementing security solutions using Amazon Web Services (AWS). This course took my understanding of cybersecurity to the next level by bridging theory with real-world application in a cloud-native environment.

From the start, the hands-on labs and project-based learning made the class engaging and fun. I worked extensively with AWS services like EC2, S3, IAM, GuardDuty, AWS WAF, and CloudTrail. One of the most memorable parts was designing secure architectures for cloud-hosted applications and setting up automated pipelines with built-in security controls.

A major highlight of the semester was building a secure CI/CD pipeline using AWS CodePipeline, CodeBuild, and EKS, integrated with Amazon Inspector for container vulnerability scanning. I learned how to write and deploy infrastructure as code using CloudFormation, enforce least privilege access with IAM policies, and detect potential threats using GuardDuty.

Another key project involved simulating threat scenarios and implementing mitigation strategies—like configuring WAF rules to block malicious IPs, using NACLs to control traffic, and setting up logging and monitoring with CloudWatch and CloudTrail to gain visibility into the environment.

This course not only gave me a deeper understanding of how cloud services operate securely but also made me confident in designing and deploying secure solutions in real AWS environments. It was an exciting journey where I got to think like both an attacker and a defender—and I walked away with a solid foundation in cloud-native security practices.

Other than doing labs, the most I am getting out of was from the final team project where I have to design a AWS to solve a particular cloud security problem I've identified:

### Here is our team's proposal for the AWS solution for the team project:
Abstract/Problem Statement: 
Many organizations today deploy their applications on containers and rely on Kubernetes to dynamically scale up and down based on factors such as the ingress traffic. Although Kubernetes is a widely used container orchestration tool due to its customizability, it is not secure by default, which can open the deployments to many different vulnerabilities. Fortunately, AWS provides various security solutions for Kubernetes, but the challenge lies in effectively implementing proper security measures. Examples of concerns include container image vulnerabilities and network attacks, like denial of service. In this project, we aim to implement Kubernetes security as part of a CI/CD pipeline, which includes steps like scanning of container images, monitoring, and threat detection.
Initial Proposal/Design: 
We will develop a secure CI/CD pipeline for Kubernetes deployments by utilizing a number of AWS security tools, which include Amazon Inspector for container image scanning, Amazon GuardDuty for threat detection, and AWS CloudTrail for activity logging. The objective is to mitigate vulnerabilities that could compromise the Kubernetes environment, securing our application from attacks. The pipeline begins when a code change is made to the application, triggering the building of the container image. From there, the image will be scanned for vulnerabilities and deployed into a Kubernetes environment. Along the way, we will be setting up network policies, rate limiting, and IP whitelisting to prevent common attack vectors like DDoS attacks and unauthorized access attempts. After it is deployed, we will monitor the application. 

Here is my team's proposal:

<div style="text-align: center;">
  <img src="{{ site.baseurl }}/assets/images/aws_pipeline.JPG" alt="AWS design architect proposal" style="max-width: 100%; height: auto;" />
  <p><strong>Could security design architect proposal using AWS from my team in the class </strong></p>
</div>

I would like to recognize and thanks for my teammate [Alexalexander Hom][Alexalexander-hom] from Wells Fargo,[Teng Loong Tee][teng-loong-tee] from Broadsome , [Sankalpa Kattel][Sankalpa-Kattel] from Akamai Technologies, and Professors who are from the secuirty industry Dr. [Rima Tanash][Rima-Tanash] from Amazaon detection service team and Ms. [Catherine Dodge][Catherine-Dodge] from Adobe for the mentoring us on the cloud security course.


[Alexalexander-hom]: https://www.linkedin.com/in/alexander-hom-94811b188/
[teng-loong-tee]: https://www.linkedin.com/in/teetengloong/
[Sankalpa-Kattel]: https://www.linkedin.com/in/sankalpa-kattel/
[Rima-Tanash]: https://www.linkedin.com/in/rima-tanash-ph-d-a53b4720/
[Catherine-Dodge]: https://www.linkedin.com/in/catherine-dodge-security/

