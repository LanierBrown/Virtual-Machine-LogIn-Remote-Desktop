
![Screenshot 2024-11-17 120051](https://github.com/user-attachments/assets/b1d9a979-fe13-4753-95f3-2bd3d82ecdc5)

# Virtual Machine LogIn (Remote Desktop)

This tutorial provides a comprehensive, step-by-step guide to creating a Virtual Machine (VM) in Microsoft Azure and accessing it for use.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- RDP (3389)


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

---


### 1️⃣ Get the Public IP Address of Your VM
- In the **Azure Portal**, go to your **Virtual Machine**'s page.
![Screenshot 2024-11-17 122318](https://github.com/user-attachments/assets/d0f4c9e6-a775-4b2f-940c-f1a37c5bb290)

  
- Under the **Overview** section, locate the **Public IP address**. This is the address you'll use to connect via RDP.

  ![Screenshot 2024-11-17 122613](https://github.com/user-attachments/assets/4a963d25-4375-4ed0-8d2b-b9411111bbc7)

---

### 2️⃣ Ensure You Have the Correct Credentials
- When configuring your VM, you would have set a **username** and **password**. Make sure you have these details ready for login.

![Screenshot 2024-11-17 122757](https://github.com/user-attachments/assets/68b3c53c-a110-4298-a858-b80ffd26f47f)


---

### 3️⃣ Launch Remote Desktop Connection (RDP)
   On your local machine:
   - **Windows**: Open **Remote Desktop Connection** by searching for **"Remote Desktop"** in the start menu.

![image](https://github.com/user-attachments/assets/5e2080dc-535e-4e19-98b4-633328538001)

     
   - **Mac**: You can use the **Microsoft Remote Desktop** app, available for free on the App Store.

---

### 4️⃣ Enter the Public IP Address
- In the **Remote Desktop Connection** window, enter the **Public IP address** of your VM obtained in Step 1.
- After entering the public IP, click **Connect**.  

  ![Screenshot 2024-11-17 123640](https://github.com/user-attachments/assets/507eb621-3c92-4643-9121-928b97f22dc5)


---

### 5️⃣ Login with Your Credentials 
- A prompt will appear asking for your **username** and **password**. Enter the credentials you set up when creating the VM.
![Screenshot 2024-11-17 124338](https://github.com/user-attachments/assets/50ac442f-d181-4116-ae43-f44f6a4ce897)

   > Example:  
   - **Username**: Virtualmachine1
   - **Password**: Your configured password

---

### 6️⃣ Confirm the Security Certificate
- The first time you connect, you may see a warning about the **identity of the remote computer**. This is normal.
- Click **Yes** or **Connect** to continue.
  
![Screenshot 2024-11-17 124541](https://github.com/user-attachments/assets/2c8b4183-dd74-4898-a0b2-d41da92e5f51)

---

### 7️⃣ You're In!
- After successful authentication, you’ll be logged into your Windows 10 Pro VM, and you’ll be able to interact with it just like a local machine.

  ![Screenshot 2024-11-17 124812](https://github.com/user-attachments/assets/ec1189a7-f519-4175-a4b9-13ebffa09bb2)


---
