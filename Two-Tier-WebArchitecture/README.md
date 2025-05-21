
# 🚀 Application Load Balancer Deployment on AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazon-aws&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-Static%20Site-blue?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Styled-lightblue?logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📄 Project Summary

This project demonstrates the deployment of a **static website** using **Amazon Web Services (AWS)** with an **Application Load Balancer (ALB)** for high availability and fault tolerance. The ALB distributes incoming traffic across **three EC2 instances**, each hosting a basic HTML/CSS website.

## 🌐 Live Demo

🔗 [Access the Load Balancer](http://load1-373467712.us-east-1.elb.amazonaws.com/)

## 🧰 Tools & Technologies

- 🟠 **Amazon Web Services (AWS)**
- 🖥️ **EC2 Virtual Machines**
- ⚖️ **Application Load Balancer (ALB)**
- 🎯 **Target Groups**
- 🌐 **HTML & CSS** (Static Website Hosting)

## ✅ Implemented Features

- ⚙️ Launched and configured **three EC2 instances**
- 🌍 Hosted a **basic HTML/CSS static site** on each instance
- 🔗 Created a **Target Group** and registered all instances
- 🧭 Configured the **Application Load Balancer** pointing to the Target Group
- 🔍 Verified functionality using the **ALB DNS endpoint**
- 📈 Monitored EC2 instance health through the **ALB dashboard**

## 📸 Architecture Overview

```text
           [ User ]
              |
         [Internet]
              |
      [Application Load Balancer]
          /       |       \
     [EC2-1]   [EC2-2]   [EC2-3]
   (Static Site) (Static Site) (Static Site)
```

## 🚀 How to Recreate This Setup

1. **Launch EC2 Instances**  
   - Create 3 EC2 t2.micro instances (Amazon Linux or Ubuntu)
   - Install and run a web server (e.g., Apache or Nginx)
   - Deploy your static HTML/CSS content

2. **Create Target Group**  
   - Register all EC2 instances
   - Use port 80 as the listener

3. **Configure ALB**  
   - Create an Application Load Balancer
   - Attach it to the correct VPC and subnets
   - Link the ALB to the previously created Target Group

4. **Testing**  
   - Access the ALB’s DNS URL to verify the site is available and traffic is balanced

## 📌 Final Thoughts

This project illustrates the practical use of an **Application Load Balancer** to build a **resilient, scalable, and production-ready** cloud architecture. By evenly distributing traffic and ensuring instance health checks, this setup offers **high availability and fault tolerance**—key principles in modern cloud-based deployments.

---

## 📬 Contact

**Syed Akmal Hussain**  
📍 Hyderabad, Telangana  
📧 akmalhussain7866@gmail.com  
📞 +91 83413 87448  
🔗 [GitHub Profile](https://github.com/Sah-IT-786)

---

> “Cloud infrastructure should not only work; it should adapt and scale seamlessly.” – Akmal
