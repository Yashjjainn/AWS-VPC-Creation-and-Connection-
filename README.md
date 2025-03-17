# AWS-VPC-Creation-and-Connection-

### Here we are going to see how to create a VPC(Virtual Private Cloud) and then how to connect it to your on premise personal computer using a site to site VPN
---

## Step 1
- Open your AWS account and navigate to VPC section and click on create VPC. It will open a window as shown below, we will opt for VPC only option since we are here to learn (VPC and more will create all the requirements for VPC automatically)
![Screenshot from 2025-03-11 16-08-04](https://github.com/user-attachments/assets/41d5b5c1-769e-4c12-a49a-a3d36e357c58)
- Give it a name via name tag option
- You can type in your own CIDR block or you can go ahead with the default CIDR that AWS gives (for our purpose we will go ahead with the default CIDR 10.0.0.0/24, which is a private IPv4 address) and click on create VPC

## Step 2
- Navigate to subnets section and click on create subnet
