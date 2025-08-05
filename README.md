# adaptix-c2-walkthrough

## Objective
A complete step-by-step walkthrough for installing, configuring, and using the Adaptix C2 post-exploitation framework on Kali Linux. This guide includes command references, setup screenshots, and instructions for generating listeners and agents for red teaming labs.

### 🧠 Skills Learned
- Deep understanding of post-exploitation and C2 frameworks  
- Practical experience configuring and deploying Adaptix C2  
- Ability to generate and manage agents and listeners  
- Familiarity with Golang-based server components and Qt-based GUI clients  
- Exposure to secure certificate generation and SSL configuration  
- Improved troubleshooting of build and runtime issues in offensive tooling  

---

### 🛠️ Tools Used
- Adaptix C2 (open-source post-exploitation framework)  
- Kali Linux (Debian-based penetration testing OS)  
- Golang (v1.24.4) for compiling the server and plugins  
- Qt6 & CMake for building the Adaptix client  
- OpenSSL for creating certificates  
- Python HTTP Server for hosting agent binaries  
- VirtualBox/VMware for setting up the test lab  

---

## 🪜 Steps

---

#### 🔹 Step 1: Cloning the Repository
- Cloned the official AdaptixC2 GitHub repository  
- Command used:  
  ```bash
  git clone https://github.com/Adaptix-Framework/AdaptixC2.git
  cd AdaptixC2

