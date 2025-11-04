# enable-cloudwatch-monitoring-for-ec2
![Alt text](https://github.com/Naveen15github/enable-cloudwatch-monitoring-for-ec2/blob/a09505ae7b1b0ef6e553e7bb6ca8e74dfb94ace4/Amazon-CloudWatch.jpg)

In this task, I enabled Amazon CloudWatch monitoring for an existing EC2 instance to track and visualize key system performance metrics such as CPU utilization, memory usage, disk activity, and network I/O.
CloudWatch helps monitor system health, optimize performance, and troubleshoot issues in real time.

## ⚙️ Steps I Performed
1️⃣ Open CloudWatch Service

Logged in to the AWS Management Console.

Opened the CloudWatch service from the AWS console search bar.

2️⃣ Enable Detailed Monitoring for EC2

Went to the EC2 console → selected my instance.

Under the Monitoring tab, clicked “Manage detailed monitoring”.

Enabled Detailed Monitoring (which provides 1-minute metric intervals instead of 5-minute basic monitoring).

Saved the settings.
Verify Metrics in CloudWatch

Went back to CloudWatch → Metrics → EC2 → Per-Instance Metrics.

Verified metrics:

CPUUtilization

mem_used_percent (Memory)

disk_used_percent (Disk)

NetworkIn / NetworkOut

 Create CloudWatch Dashboard

Created a new dashboard named EC2-Monitoring-Dashboard.

Added widgets for CPU, Memory, Disk, and Network I/O graphs.

This helps visualize instance performance in real time.

## 📊 Output
![Alt text](https://github.com/Naveen15github/enable-cloudwatch-monitoring-for-ec2/blob/a09505ae7b1b0ef6e553e7bb6ca8e74dfb94ace4/Screenshot%20(108).png)

CloudWatch dashboard now displays real-time EC2 performance metrics.

Alerts configured for high CPU or memory usage.

Helps ensure instance health and proactive monitoring.

## 🧠 What I Learned

Difference between basic and detailed monitoring.

How to install and configure CloudWatch Agent.

How to visualize metrics in dashboards and create alarms.

## ✅ Status: Completed Successfully

All metrics (CPU, Memory, Disk, Network I/O) are visible and monitored through Amazon CloudWatch.
