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

- In the Azure portal, use the search bar to look for **"Resource Groups"** and click to open it.
- In the top-left corner, click **Create** to begin the process.

![Resource Groups1](https://github.com/user-attachments/assets/d569520b-d7f3-4387-a046-b1b71c5497ac)  
![Resource Group2](https://github.com/user-attachments/assets/db635c7f-b67d-4a76-9c5b-2631a121c520)

- Select your **Subscription**.
- Enter a **Resource Group Name**.
- Choose the **Region** closest to you.
- Scroll down and click **Review + Create** at the bottom.

![Resource Groups3](https://github.com/user-attachments/assets/caff40f9-10fe-4018-8c3a-04103a8fba93)

- Once validation passes, click **Create** to finish.

![Resource Groups4](https://github.com/user-attachments/assets/39eb199b-bd6b-4323-a546-ec61146ebb84)


## 🪟 Step 2: Create the Windows 10 Virtual Machine

- In the Azure portal, use the search bar to look for **"Virtual Machines"** and click to open it.
- On the **Virtual Machines** page, click **Create**, then select **"Virtual Machine"** to begin the setup process.

![Virtual Machines1](https://github.com/user-attachments/assets/573a48a7-e10b-4de2-9ac2-f09d63c59ee2)  
![Virtual Machines2](https://github.com/user-attachments/assets/79e868a3-497c-408f-a3c1-c2f745a969e9)

- Select the **Resource Group** you just created.
- Name your Virtual Machine.
- Choose the **Region** that matches your Resource Group.

![Virtual Machines3](https://github.com/user-attachments/assets/a0b42ba4-5e63-4810-aedc-01b4fcc48a27)

- For the **Image**, select **Windows 10 Pro**.
- For the **Size**, choose an option with at least **2 vCPUs** to avoid slowness.  
  > 💡 If you don't see that option right away, click **"See all sizes"**.

![Virtual Machines4](https://github.com/user-attachments/assets/d8bbbe40-52d0-481a-b71f-9ef32f028faa)

- Create a **Username** and **Password** for your VM.
- Scroll down and **check the box to confirm the Windows licensing terms**.  
  > ⚠️ If you skip this step, Azure will show an error and won’t pass the validation.

- Click **Review + Create** to proceed.

![Virtual Machines5](https://github.com/user-attachments/assets/d8fb4e53-67ec-4a63-b216-ba1876effc2a)

- If **Validation passes** and your settings look correct, click **Create** to deploy the VM.

![Virtual Machines6](https://github.com/user-attachments/assets/a1481572-7ced-4697-9af8-bef2f245bd4f)

> ✅ **Deployment will take a few minutes**. Once complete, your Windows 10 VM will be ready to use.

---

## 🐧 Step 3: Create a Linux (Ubuntu) Virtual Machine

- In the Azure portal, use the search bar to look for **"Virtual Machines"** and click to open it.
- On the **Virtual Machines** page, click **Create**, then select **"Virtual Machine"** to begin the setup process.

![Virtual Machines1](https://github.com/user-attachments/assets/573a48a7-e10b-4de2-9ac2-f09d63c59ee2)  
![Virtual Machines2](https://github.com/user-attachments/assets/79e868a3-497c-408f-a3c1-c2f745a969e9)

- Select the **Resource Group** you just created.
- Name your Virtual Machine.
- Choose the **Region** that matches your Resource Group.

![Virtual Machines3](https://github.com/user-attachments/assets/a0b42ba4-5e63-4810-aedc-01b4fcc48a27)

- For the **Image**, select **Ubuntu 22.04 LTS**.
- For the **Size**, choose an option with at least **2 vCPUs** to avoid slowness.  
  > 💡 If you don't see that option right away, click **"See all sizes"**.

![Virtual MachinesL1](https://github.com/user-attachments/assets/c45e91b0-1390-4953-a240-1453455bea27)

- For **Authentication Type**, select **Password** instead of the default **SSH public key**.
- Create a **Username** and **Password** for your VM.
- Click **Next** twice to proceed to Networking.

![Virtual MachinesL2](https://github.com/user-attachments/assets/a2bdff63-969f-4dc0-81ff-352cbbbb9303)

- Under **Networking**, make sure to use the **same virtual network** as your Windows VM.
- Leave the remaining settings at default.
- Click **Review + Create**, then click **Create**.

![Virtual MachinesL3](https://github.com/user-attachments/assets/a6b431a8-3210-4d51-ac00-31bdb3177e79)

> ✅ Wait a few minutes for the VM to deploy.

- Once the deployment is complete, return to the **Virtual Machines** page to see both your Windows and Linux VMs listed and running.

![Virtual MachinesL4](https://github.com/user-attachments/assets/baa0062e-501d-41f8-9772-4b86230db24b)

---
## 🧾 Conclusion

We successfully created a **Resource Group**, a **Windows 10 Virtual Machine**, and a **Linux Ubuntu Virtual Machine** in Microsoft Azure. These VMs will be used for upcoming labs and practice environments.

> 💡 **Tip:** If you're not done using these VMs, it's a good idea to keep them for future labs.  
> ⚠️ If you don’t plan on using the VMs right away, be sure to **stop** them — otherwise, Azure will charge you while they are running.  
> If you plan to use them soon, you can leave them **running** or **start** them later from the Azure portal.
