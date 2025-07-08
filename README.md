# 🚨 AWS CloudWatch CPU Utilization Alarm

A step-by-step setup for monitoring EC2 instance CPU usage using **Amazon CloudWatch** and triggering real-time alerts via **SNS (Simple Notification Service)**.

## 📊 Project Objective

To automatically monitor the **CPU usage** of an EC2 instance and send notifications when it exceeds a defined threshold.

---

## 🛠️ Tech Stack

- **AWS EC2**
- **Amazon CloudWatch**
- **Amazon SNS**
- **IAM Roles**

---

## 📸 Setup Screenshots

| Step | Screenshot |
|------|------------|
| CloudWatch Dashboard | ![](screenshots/1_dashboard.png) |
| Selecting EC2 Metrics | ![](screenshots/2_metrics_selection.png) |
| Alarm Configuration | ![](screenshots/3_alarm_config.png) |
| Alarm Created Successfully | ![](screenshots/4_alarm_success.png) |

---

## 📦 Steps to Recreate This Project

1. Launch an EC2 instance and ensure it's running.
2. Install and configure **CloudWatch Agent** on the instance.
3. Go to `CloudWatch > Alarms` → Create Alarm.
4. Choose **EC2 CPUUtilization** metric.
5. Set a threshold (e.g., > 80%).
6. Configure **SNS topic** for notifications.
7. Confirm email subscription.
8. Done! Alarm is now active.

---

## ✅ Outcome

- 🧠 Real-time CPU monitoring enabled
- 🔔 Email alert received on threshold breach
- 🔒 No cost if under **Free Tier**

---

## 📬 Sample Email Notification

> *Subject:* ALARM: "cloudwatch cpu alarm" in Asia Pacific (Mumbai)  
> *Message:* CPUUtilization > 80 for 5 minutes

---

## 📚 Learnings

- AWS monitoring without coding
- Smart alert systems using SNS
- Importance of real-time system health tracking

---

## ✨ Future Scope

- Monitor RAM & disk usage
- Integrate with **Lambda** for auto-scaling
- Add **Slack or webhook** integration for DevOps workflows

---

## 🧑‍💻 Author

**Aarohi Goel**  
CSE Final Year Student | Cloud Enthusiast | Full Stack Learner  


---

