
![Screenshot 2024-11-17 120051](https://github.com/user-attachments/assets/b1d9a979-fe13-4753-95f3-2bd3d82ecdc5)

# Virtual Machine LogIn (Remote-Desktop)

This tutorial provides a comprehensive, step-by-step guide to creating a Virtual Machine (VM) in Microsoft Azure and accessing it for use.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Resource Groups
- RDP (3389)


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

---


### 1️⃣ Get the Public IP Address of Your VM
- In the **Azure Portal**, go to your **Virtual Machine**'s page.  
- Under the **Overview** section, locate the **Public IP address**. This is the address you'll use to connect via RDP.

   ![Public IP Address](images/public_ip_address.png)

---

### 2️⃣ Ensure You Have the Correct Credentials
- When configuring your VM, you would have set a **username** and **password**. Make sure you have these details ready for login.

---

### 3️⃣ Launch Remote Desktop Connection (RDP)
   On your local machine:
   - **Windows**: Open **Remote Desktop Connection** by searching for **"Remote Desktop"** in the start menu.
   - **Mac**: You can use the **Microsoft Remote Desktop** app, available for free on the App Store.

---

### 4️⃣ Enter the Public IP Address
- In the **Remote Desktop Connection** window, enter the **Public IP address** of your VM obtained in Step 1.

   > Example: `123.45.67.89`

---

### 5️⃣ Login with Your Credentials
- After entering the public IP, click **Connect**.  
- A prompt will appear asking for your **username** and **password**. Enter the credentials you set up when creating the VM.

   > Example:  
   - **Username**: `adminuser`  
   - **Password**: Your configured password

---

### 6️⃣ Confirm the Security Certificate
- The first time you connect, you may see a warning about the **identity of the remote computer**. This is normal.
- Click **Yes** or **Connect** to continue.

---

### 7️⃣ You're In!
- After successful authentication, you’ll be logged into your Windows 10 Pro VM, and you’ll be able to interact with it just like a local machine.

---
