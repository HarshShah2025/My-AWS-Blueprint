# ☁️ AWS Cloud Fundamentals

This note covers the most essential cloud concepts you must know before diving into AWS services.

---

## ☁️ What is Cloud Computing?

Cloud computing is the **on-demand delivery** of IT resources (like servers, storage, databases) over the internet with **pay-as-you-go** pricing.

### 🔑 Key Features:
- No upfront hardware cost 🖥️  
- Scalable and elastic 📈  
- Accessible anytime, anywhere 🌐  
- Maintenance is handled by cloud provider 🧰  

---

## 🏢 Cloud Deployment Models

1. **Public Cloud** – Services offered over the internet (e.g., AWS, Azure)  
2. **Private Cloud** – Used exclusively by one organization  
3. **Hybrid Cloud** – Combination of both public and private

---

## 🔧 Cloud Service Models

1. **IaaS** (Infrastructure as a Service)  
   - Virtual machines, storage, networking  
   - e.g., AWS EC2, S3

2. **PaaS** (Platform as a Service)  
   - Environment to develop and deploy applications  
   - e.g., AWS Elastic Beanstalk

3. **SaaS** (Software as a Service)  
   - Ready-to-use applications  
   - e.g., Gmail, Zoom

---

## 📦 Virtualization & Hypervisors

Virtualization allows us to run **multiple virtual machines (VMs)** on one physical server using software called a **hypervisor**.

- **Hypervisors**:  
  - Type 1: Runs directly on hardware (e.g., VMware ESXi)  
  - Type 2: Runs on host OS (e.g., VirtualBox)

> 🔥 AWS uses virtualization to power EC2 instances.

---

## 🌍 AWS Global Infrastructure

- **Region**: Geographical area (e.g., us-east-1) 🌎  
- **Availability Zone (AZ)**: Data centers inside a region 🏢  
- **Edge Location**: For content delivery (CDN) via CloudFront 🚀

---

## 🔄 Shared Responsibility Model

- **AWS manages**: Hardware, network, hypervisor, data center  
- **You manage**: Data, access, configuration, software updates

> Example: AWS secures the building, you secure your passwords 🔐

---

## 💰 AWS Pricing Basics & Free Tier

- **Pay-as-you-go**: Pay only for what you use  
- **Free Tier**:  
  - 750 hrs/month EC2 t2.micro  
  - 5 GB S3  
  - 25 GB DynamoDB  
  - Good for learning/testing!

---

🧠 **Remember**:  
Understanding these basics will make every AWS service easier to grasp.

