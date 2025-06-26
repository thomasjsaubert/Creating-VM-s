![Microsoft Azure](https://summ-it.eu/wp-content/uploads/2022/08/image10az.png)

# 🧱 Creating a Virtual Machine (Windows and Linux) Using Azure

This tutorial outlines the process for creating Virtual Machines in Azure — including both Windows and Linux environments.

---

## 🛠️ Prerequisites

- A valid [Microsoft Azure Account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account/)

---

## 💻 Environments and Technologies Used

- Microsoft Azure Cloud Platform

---

## 🖥️ Operating Systems Used

- Windows 10 (22H2)
- Linux Ubuntu (Latest LTS)

---

## 🧭 Steps We Will Follow

1. Create a Resource Group in Azure  
2. Create a Windows 10 Virtual Machine  
3. Create a Linux Ubuntu Virtual Machine  

---

## ⚙️ Step 1: Create a Resource Group

- In the Azure portal, search for **"Resource Groups"** and select it.
- Click **Create**.

![Step 1a](https://github.com/user-attachments/assets/8ed62e36-488a-443e-ab73-839f54cffa3e)
![Step 1b](https://github.com/user-attachments/assets/3e024aba-d653-48e3-945f-4968becf4553)

- Select your **Subscription**.
- Enter a **Resource Group Name**.
- Choose a **Region** closest to you.
- Click **Review + Create**.

![Step 1c](https://github.com/user-attachments/assets/4b253bbc-ce0c-46df-8eac-fbf8187f9562)

- Once validated, click **Create**.

![Step 1d](https://github.com/user-attachments/assets/949d869f-5867-43b1-a243-1ba378a3f994)

---

## 🪟 Step 2: Create the Windows 10 Virtual Machine

- In Azure, search for **"Virtual Machines"**, then click **Create** → **Virtual Machine**.

![Step 2a](https://github.com/user-attachments/assets/d79c9081-f3af-4780-8c94-aecdacf02bc9)

- Select the **Resource Group** you just created.
- Name your virtual machine.

![Step 2b](https://github.com/user-attachments/assets/1b58f672-d20f-435a-8854-6a12ff21521e)

- Select an **Availability Zone**.
- For the **Image**, choose **Windows 10 Pro**.
- For **Size**, choose one with at least **2 vCPUs** to avoid slowness.

![Step 2c](https://github.com/user-attachments/assets/b997f4aa-d59b-4a6f-8fc3-95d143fb104d)

- Create a **username and password**.
- Confirm **licensing terms**.
- Click **Review + Create**.

![Step 2d](https://github.com/user-attachments/assets/7e984696-a66e-44d1-b39b-9aae13d4c302)

- Review the settings and click **Create**.

![Step 2e](https://github.com/user-attachments/assets/bd4e5f77-6eed-4c5d-9930-95e7b5516680)

> ✅ The deployment will take a few minutes.

---

## 🐧 Step 3: Create a Linux (Ubuntu) Virtual Machine

- Repeat the steps from above with these changes:
  - Use the **same Resource Group**.
  - Choose **Ubuntu Server** as the image.

![Step 3a](https://github.com/user-attachments/assets/3a7f7148-5e51-44a5-bc81-65c7faf5e52b)

- For **Authentication Type**, select **Password** instead of the default SSH key.
- Create a **username and password**.

![Step 3b](https://github.com/user-attachments/assets/7a1d0698-7e74-4f52-9941-c0757dc25468)

- Under **Networking**, make sure to use the **same virtual network** as your Windows VM.

![Step 3c](https://github.com/user-attachments/assets/9b8999ca-69ab-4f8a-8d68-682a07921c5c)

- Leave other options at default, then click **Review + Create** → **Create**.

![Step 3d](https://github.com/user-attachments/assets/56278c5d-bdfd-41f8-b3aa-aa2bc7d8b736)

> ✅ Wait a few minutes for the VM to deploy.

![Step 3e](https://github.com/user-attachments/assets/f4df4b67-1c41-45b3-96f3-5b048aec79a1)

- Go to **Resource Groups** to view both of your VMs.

![Step 3f](https://github.com/user-attachments/assets/8d61580f-2be4-4985-a472-c00375e28101)
![Step 3g](https://github.com/user-attachments/assets/c5fe4f42-aa2d-4fe6-87e6-38724b5b86f6)

- ⚠️ If you aren’t using the VMs immediately, **stop them** to avoid charges.
- If you're using them soon, leave them **running** or **turn them on** when needed.

![Step 3h](https://github.com/user-attachments/assets/8a9f86d2-d940-4929-9f56-f1923edc0d90)

---

## 🧾 Conclusion

We successfully created a Resource Group, a Windows 10 Virtual Machine, and a Linux Ubuntu Virtual Machine in Microsoft Azure. These VMs will be used for upcoming labs and practice environments.

> 💡 **Tip:** Unless you're done with them, it's a good idea to keep these VMs and not delete them yet.
