# ☁️ AWS Cloud Portfolio Project

A personal portfolio website deployed on a **fully scalable, highly available AWS infrastructure** — built hands-on to demonstrate real-world cloud skills.

-----

## 🌐 Project Overview

This project is a static personal portfolio website showcasing my skills, background, and transition from Finance to Cloud Technology. The focus of the project is not just the frontend — but the **AWS architecture behind it**: a production-grade, auto-scaling deployment capable of handling variable traffic loads.

-----

## 🏗️ AWS Architecture

|Service                  |Role                                                     |
|-------------------------|---------------------------------------------------------|
|**Amazon S3**            |Stores static website assets (HTML, CSS, JS, images)     |
|**Amazon EC2**           |Hosts the web server instances                           |
|**Auto Scaling Group**   |Automatically adds/removes EC2 instances based on traffic|
|**Elastic Load Balancer**|Distributes incoming traffic evenly across EC2 instances |
|**Target Group**         |Routes load balancer traffic to healthy EC2 instances    |

### Architecture Flow

```
User Request
     ↓
Elastic Load Balancer
     ↓
Target Group (health checks)
     ↓
Auto Scaling Group (EC2 Instances)
     ↓
Static Assets served from S3
```

-----

## 💻 Frontend

Built with plain HTML, CSS, and JavaScript — no frameworks, keeping it lightweight and fast.

- `index.html` — Main portfolio page
- `style.css` — Styling and layout
- `script.js` — Interactive elements
- `cloud.jpg` — Hero image
- `img&SS/` — AWS architecture screenshots

-----

## 📸 Screenshots

The `img&SS/` folder contains real screenshots from the AWS Console:

- ✅ S3 Bucket configuration
- ✅ EC2 Instance setup
- ✅ Auto Scaling Group
- ✅ Load Balancer
- ✅ Target Group
- ✅ Live website

-----

## 👩‍💻 About Me

**Saniya** | BBA Finance (CGPA 8.1) → Cloud Technology  
📍 Nagpur, India  
🎯 Aspiring Cloud Support Engineer | AWS Cloud Practitioner (CLF-C02) in progress  
💡 Finance background + AWS hands-on experience = business-aware cloud professional

🔗 [LinkedIn](https://www.linkedin.com/in/saniya-upadhyay-420910201) 

-----

## 🚀 Key Learnings

- Configured a **highly available** architecture using Load Balancer + Auto Scaling
- Understood how **Target Groups** perform health checks on EC2 instances
- Hands-on experience deploying and managing **EC2 instances**
- Hosted static assets on **S3** as part of a multi-service architecture

-----

*Built independently as a hands-on AWS learning project — every service configured from scratch.*
