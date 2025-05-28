# 🌍 AWS Global Infrastructure - Hands-On Lab

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

---

### ♦️View availability zones
1. Open the **EC2 Dashboard**
2. On the left, click **Limits**, then find "Running On-demand standard (A,C,D,H,I,M,R,T.Z) instances"
3. Select a region and see the number of AZs (typically 2-6 per region)

---

### ♦️Exploring edge locations (CloudFront)
1. Navigate the AWS console homepage
2. Search for **Amazon CloudFront** and open it
3. Click **Create Distribution**
4. View the settings which uses EdgeLocations to cache content for users worldwide

---

## 🔎 Reflection Questions

> 💬 What is an AWS Region?
> 💬 Why are AZs considered to be important?
> 💬 WHat are Edge Locations used for?

---

## ✅ Checklist summary
-[x] Able to identify default AWS regions via console
-[x] Viewed AZs informations in EC2 limits
-[x] Explored CloudFront distribution settings
