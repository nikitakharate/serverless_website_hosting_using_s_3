# Serverless Website Hosting

## Introduction
This project demonstrates how to host a **static website using a fully serverless approach**. The website is deployed using an Amazon S3 bucket without provisioning or managing any servers.

Serverless website hosting is a cost-effective and scalable solution for hosting static websites such as portfolios, landing pages, and documentation sites.

---

## Project Objective
- Host a static website without using EC2 or traditional servers
- Configure public access for static content
- Understand S3 bucket permissions and ACL settings
- Deploy and access a live website through a browser

---

## Architecture Overview
[![s2.png](https://i.postimg.cc/VkPTJck4/s2.png)](https://postimg.cc/ppkkS48n)
Client (Browser)
        ↓
S3 Bucket (Static Website Files)
        ↓
Public Access Configuration
        ↓
Website Endpoint URL

This architecture eliminates the need for:
- Web servers
- Operating system management
- Scaling configuration

---

## Technologies Used
- Amazon S3
- Static HTML/CSS/JS
- Access Control Lists (ACL)

---

## Step-by-Step Implementation

### Step 1: Create an S3 Bucket
- Logged into AWS Console
- Navigated to S3 service
- Clicked on "Create bucket"
- Provided a unique bucket name
- Selected appropriate region
[![Whats-App-Image-2026-03-01-at-10-11-48-AM.jpg](https://i.postimg.cc/vTQTYKxz/Whats-App-Image-2026-03-01-at-10-11-48-AM.jpg)](https://postimg.cc/9RnC1JpR)
---

### Step 2: Enable ACLs
- During bucket creation, selected ACL enabled option
- Allowed management of object-level permissions
[![s3.jpg](https://i.postimg.cc/zBh2ztYL/s3.jpg)](https://postimg.cc/r08Ng9mc)
---

### Step 3: Remove Block Public Access
- Disabled "Block all public access"
- Confirmed acknowledgment warning

This step allows the website content to be accessible over the internet.
[![s4.jpg](https://i.postimg.cc/RF11pjzy/s4.jpg)](https://postimg.cc/MMTjv3Hm)
---

### Step 4: Create Bucket Successfully
- Reviewed configuration
- Created the bucket
[![s5.jpg](https://i.postimg.cc/wjShq6xg/s5.jpg)](https://postimg.cc/0z06Z1JB)
---

### Step 5: Upload Static Website Files
- Uploaded static website files (HTML, CSS, JS)
- Example: index.html

---

### Step 6: Make Files Public
- Selected uploaded files
- Modified object permissions
- Enabled public read access

This allows users to access the content directly from the browser.
[![s6.jpg](https://i.postimg.cc/Dfj4f25x/s6.jpg)](https://postimg.cc/qgKvjHPK)
---

### Step 7: Access Website via Browser
- Copied the S3 object URL or website endpoint
- Opened the URL in a web browser
- Successfully displayed the website
[![s8.jpg](https://i.postimg.cc/9M40r9Ls/s8.jpg)](https://postimg.cc/2bDrt1Rx)
[![s7.jpg](https://i.postimg.cc/VvCwcBDZ/s7.jpg)](https://postimg.cc/MfqN7Rk1)
---

## Key Features
- Fully serverless deployment
- No server management required
- Low-cost hosting solution
- Highly scalable infrastructure
- Suitable for portfolio and static sites

---

## Advantages of Serverless Website Hosting
- Reduced operational overhead
- Pay only for storage used
- High durability and availability
- Easy deployment and maintenance

---

## Limitations
- Supports only static websites
- No backend processing without additional services
- Requires proper permission management

---

## Conclusion
This project successfully demonstrates serverless website hosting using Amazon S3. By eliminating the need for traditional servers, the solution provides a scalable, cost-effective, and simple hosting environment for static web applications.

The project reflects practical cloud deployment knowledge and a strong understanding of serverless architecture principles.

---

**Project Implemented Using Serverless Cloud Architecture** 

