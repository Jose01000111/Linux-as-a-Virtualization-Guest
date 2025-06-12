# 🚀LPIC-1 102.6 — Linux as a Virtualization Guest

### In this lab, I explored how Linux behaves as a virtualization guest 🐧 — specifically using CentOS on Hyper-V 💾 and an AWS EC2 instance ☁️. Understanding these environments helps me configure and manage Linux systems in virtualized and cloud-native infrastructure. 🧑‍💻🔧

## 1️⃣ 🔍 Detect the Virtualization Environment

🔹 Command:

## 2️⃣ 📦 Check for Cloud-Init and Guest Tools

🔹 Check for cloud-init config:

🔹 Check for Hyper-V guest drivers:

## 3️⃣ 🔐 Verify and Reset Machine ID (For Cloning)

🔹 Command to check machine ID:

🔹 To reset it properly:

## 4️⃣ 💾 Check Storage & Network in Virtual Environment

🔹 List block devices:

🔹 Check virtual NICs and IP config:

## 5️⃣ 🐳 Inspect Containers Running Inside the VM

🔹 If containers were installed, I could view them with:

## 💡 What I Learned
In this lab, I learned how to detect, inspect, and manage CentOS as a virtualization guest in Hyper-V.
