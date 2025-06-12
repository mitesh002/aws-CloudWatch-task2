# Task 2 – AWS Cloud Monitoring and Alerts (CloudWatch)

## 🛠 Setup Summary
- Launched EC2 instance (t2.micro) in Free Tier
- Enabled default EC2 monitoring (CPU, Network, Disk)
- Created CPU utilization alarm
- Built CloudWatch dashboard with key widgets

## 📊 Metrics Used
- CPUUtilization
- NetworkIn
- DiskReadOps

## 📉 CloudWatch Alarm
- Threshold: CPU > 60% for 5 mins
- Action: Email notification (SNS)

## 🖥️ Dashboard
- Created: `EC2MonitoringDashboard`
- Included widgets: CPU trend, network traffic, disk ops

## 💸 Cost Management
- Used t2.micro (Free Tier)
- No custom metrics or logs
- EC2 stopped after task
