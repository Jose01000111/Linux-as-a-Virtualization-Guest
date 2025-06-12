# 🚀LPIC-1 102.6 — Linux as a Virtualization Guest

In this lab, I explored how CentOS Stream functions as a virtualization guest when running inside Microsoft Hyper-V 💾.
This is critical for system administrators who work in virtualized environments and need to manage templates, clones, and system behavior when Linux is not installed on bare metal.

I’ve included some helpful links to guide you through the lab and for studying afterward:

[LPIC Exam Objective 102.6](https://www.lpi.org/our-certifications/exam-101-102-objectives/#102.6_Linux_as_a_virtualization_guest)

[102.6 NOTES](https://1drv.ms/w/c/354f1c8d534fbced/Ee6eVvuo-qFLrEGn088N5YoBk0cUzsyNJQfGiHcyAy6qeA?e=5bnqeJ)

[102.6 LAB](https://1drv.ms/w/c/354f1c8d534fbced/EW0dIcwA_5BDunfZOg3nE74BzW67816K2siHqYrIIQbbtg?e=YdCQKu)

---

## 1️⃣ 🔍 Detect the Virtualization Environment

🔹 Command:

![HbyWf4o](https://github.com/user-attachments/assets/61582e93-026d-4c58-b24d-aab167c1ba89)

## 2️⃣ 📦 Check for Cloud-Init and Guest Tools

🔹 Check for cloud-init config:

![Zm2VT6H](https://github.com/user-attachments/assets/23ac97ce-0980-4f2e-bb59-bfbf3b88da8d)

🔹 Check for Hyper-V guest drivers:

![kxqGVt6](https://github.com/user-attachments/assets/579fed1c-1893-45b0-8beb-2eee88113f14)

## 3️⃣ 🔐 Verify and Reset Machine ID (For Cloning)

🔹 Command to check machine ID:

🔹 To reset it properly:

![UflXazy](https://github.com/user-attachments/assets/c08e2105-4011-4075-9662-2d1774657b62)

![zmLc7oA](https://github.com/user-attachments/assets/b3440510-c44f-4bd8-898c-50c03df1c7e6)

## 4️⃣ 💾 Check Storage & Network in Virtual Environment

🔹 List block devices:

![b1dKIou](https://github.com/user-attachments/assets/667fb2d5-92bf-4605-8a11-3137ddb8e212)

🔹 Check virtual NICs and IP config:

![Bqv5lVe](https://github.com/user-attachments/assets/46ef96b5-409e-41d5-9d2c-b0a076a8fb11)

## 5️⃣ 🐳 Inspect Containers Running Inside the VM

🔹 If containers were installed, I could view them with:

![5YNfhBR](https://github.com/user-attachments/assets/a5e93dcb-47ce-4ee8-8095-32801998d635)

![LT1Esih](https://github.com/user-attachments/assets/9db0ca31-93b6-4ada-ae6e-13d9be775b3c)

## 💡 What I Learned
In this lab, I learned how to detect, inspect, and manage CentOS as a virtualization gues
t in Hyper-V.







