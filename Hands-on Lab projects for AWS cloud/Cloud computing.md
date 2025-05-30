# ☁️ Cloud concepts - Hands-On Lab

## ⚡️ Lab Title: "Exploring Cloud Advantages with EC2 and S3"

---

## 🎯 Objectives
- Understand core cloud concepts such as om-demand delivert, elasticity and pay-as-you-go-pricing
- Launch and manage EC2
- Use S3 for scalable object storage
- Reflect on how AWS illustrates cloud benefits

---

## Instructions

### ♦️ Launch an EC2 Instance (On-demand provisioning)
1. Navigate to the EC2 Dashboard on the AWS Console [https://aws.amazon.com/console/]  
2. Click **Launch Instance**
3. Name the instance `Module1-Demo-EC2`
4. Choose **Amazon Linux 2 AMI**
5. Select Instance type: **t2.micro**
6. Keep default configurations and launch with a new key pair or an existing one
7. Once running, **stop the instance** to stimulate cost efficiency

  ![IMG_2231](https://github.com/user-attachments/assets/a115d846-8be7-4e42-8428-953daec7d719)
  
  ![IMG_2233](https://github.com/user-attachments/assets/36e044fa-e0f8-47f5-a114-78d44543f6af)
  
  ![IMG_2236](https://github.com/user-attachments/assets/779af733-335e-4063-a943-716c40c2045f)
  
  ![IMG_2237](https://github.com/user-attachments/assets/56a3820a-48ce-4fbc-874d-1db0d6a5a5ce)
  
  ![IMG_2239](https://github.com/user-attachments/assets/f459bfec-e4c4-4109-8627-eafb3332c796)
  
  ![IMG_2241](https://github.com/user-attachments/assets/ac565aa0-f62c-4150-bc15-26081b384a81)

---

### ♦️ Create and Use an S3 bucket (Scalability)
1. Navigate the S3 Services in AWS
2. Click **Create Bucket**, name it `module1-demo-s3-bucket`
3. All settings were left at default for demo purposes
4. Upload a sample image to the bucket

![IMG_2243](https://github.com/user-attachments/assets/cdcfc51c-8769-4e9a-86ed-a41f170eaecb)

![IMG_2245](https://github.com/user-attachments/assets/c9f1db9d-0adf-4761-a399-95400677250a)

![IMG_2247](https://github.com/user-attachments/assets/94f5d972-59cd-45ed-8a19-a22af3a3ccbf)

![IMG_2249](https://github.com/user-attachments/assets/23812c8f-5a1f-4ca7-8727-4d34f46ec8ee)

---

### ♦️ Explore Billing (Pay-As-You-Go)
1. Visit [https://console.aws.amazon.com/billing/home#/]
2. View the **Free Tier Usage**
3. Note that no charges for resources were made within the free tier limits

![IMG_2251](https://github.com/user-attachments/assets/2d85ba25-e18a-43b2-8f83-3cea49983a76)

---

## 🔎 Reflection

> 💬 **What does 'on-demand' mean in AWS?**

> Resources provided by AWS can be launched and used whenever you need them, billing will be charged per hour or second, depending on the service acquired

> 💬 **How does S3 demonstrates scalability?**

> Through the automation in handling virtually unlimited storage and access requests without requiring any manual intervention

> 💬 **Why is AWS considered cost-effective?**

> It aids individuals using it by reducing IT costs while offering a scalable, pay-as-you-go services avoiding the high expenses of traditional infastructure

---

## ✅ Completion checklist

- [x] Launched and stopped an EC2 instance
- [x] Created S3 bucket and uploaded file
- [x] Reviewed AWS billing
- [x] Navigated my way around AWS console webpage
