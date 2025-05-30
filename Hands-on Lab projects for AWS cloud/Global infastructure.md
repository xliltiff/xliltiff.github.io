![IMG_2257](https://github.com/user-attachments/assets/6b1d67f7-c774-4d1c-9e3c-395266a4a0c6)# 🌍 AWS Global Infrastructure - Hands-On Lab

## ⚡️ Lab Title: "Exploring AWS Regions, Availability Zones and Edge Locations"

---

## 🎯 Objectives
- Understand AWS's global infrastructure: Regions, Availability zones and Edge locations
- Using AWS Console to identify default region
- Learn how services behave across different regions

---

## Instructions

### ♦️Identifying your default region
1. Sign in to the [AWS Console]
2. Identify the top right and note the region name stated
3. Locate the dropdown icon to explore all available regions

![IMG_2253](https://github.com/user-attachments/assets/fba2ccec-f47b-4986-8caf-b0ccd514661a)

![IMG_2257](https://github.com/user-attachments/assets/619dce25-3d43-46a7-8d94-96111cb4053d)

---

### ♦️View availability zones
1. On the searchbar look for **Service Quotas**
2. In the searchbar of Service Quotas look for **Amazon Elastic Comput Cloud (Amazon EC2)**
3. On the left, click **Limits**, then find "Running On-demand standard (A,C,D,H,I,M,R,T.Z) instances"
4. Select a region and see the number of AZs (typically 2-6 per region)

![IMG_2258](https://github.com/user-attachments/assets/dcc98085-06c2-4300-85f0-c0fea27bb219)

![IMG_2259](https://github.com/user-attachments/assets/7b781cc4-a6dd-4a38-92c5-d8d7abf77721)

- This is the region for Singapore ap-southeast-1

![IMG_2260](https://github.com/user-attachments/assets/0b9ffa56-7d06-4d97-aa16-c776c4dae0d2)

- This is the region for United States (Oregon) us-west-2

---

### ♦️Exploring edge locations (CloudFront)
1. Navigate the AWS console homepage
2. Search for **Amazon CloudFront** and open it
3. Click **Create Distribution**
4. View the settings which uses EdgeLocations to cache content for users worldwide

![IMG_2261](https://github.com/user-attachments/assets/c3b2416a-3a07-493c-82f8-bb54eb79ec85)

![IMG_2266](https://github.com/user-attachments/assets/773d7fd2-aa58-4e92-8666-c60c65aef588)

---

## 🔎 Reflection Questions

> 💬 What is an AWS Region?

> It's a physical geographic location where a group of data centers are located in the Amazon Web services

> 💬 Why are AZs considered to be important?

>They provide high availability, fault tolerance and scalability

> 💬 What are Edge Locations used for?

> Used for delivering content to end users quicker through caching and processing data closer to where the users are located

---

## ✅ Checklist summary
- [x] Able to identify default AWS regions via console
- [x] Viewed AZs informations in EC2 limits
- [x] Explored CloudFront distribution settings
