![microsoft-azure](https://summ-it.eu/wp-content/uploads/2022/08/image10az.png)


<h1>Creating a Virtual Machine (Windows and Linux) using Azure</h1>
This tutorial outlines the setup process for creating a Virtual Machine using Azure, and we will be creating Windows and Linux

<h2>Prerequisite</h2>

  - [Microsoft Azure Account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account/search?ef_id=_k_Cj0KCQjwzYLABhD4ARIsALySuCTvMpKHbOeSo9lv81A8vCg1XGDNwpOIuOsD2o8pmLnyl7dVku-Yn3IaApK-EALw_wcB_k_&OCID=AIDcmmfq865whp_SEM__k_Cj0KCQjwzYLABhD4ARIsALySuCTvMpKHbOeSo9lv81A8vCg1XGDNwpOIuOsD2o8pmLnyl7dVku-Yn3IaApK-EALw_wcB_k_&gad_source=1&gbraid=0AAAAADcJh_uVoYZIZMJRJFQ3v8k-BGmp2&gclid=Cj0KCQjwzYLABhD4ARIsALySuCTvMpKHbOeSo9lv81A8vCg1XGDNwpOIuOsD2o8pmLnyl7dVku-Yn3IaApK-EALw_wcB)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Linux Ubuntu

<h2>Steps We Will Take</h2>

  - Step 1: Create a Resource Group in Azure
  - Step 2: Create the Windows 10 VM in Azure
  - Step 3: Create the Linux Ubuntu VM in Azure

<h2>Process in Creating the Virtual Machine in Azure</h2>

<h2>Step 1 - Create a Resource Group</h2>

  - Click on the search bar and type "Resource Groups" or until you see it
  - Then select "Resource Groups"

![Creating-Azure-Part1a](https://github.com/user-attachments/assets/8ed62e36-488a-443e-ab73-839f54cffa3e)

  - Select "Create"

![Creating-Azure-Part1b](https://github.com/user-attachments/assets/3e024aba-d653-48e3-945f-4968becf4553)

  - Select your preferred "Subscription"
  - Name your Resource Group
  - Select the region closest to you
  - Select "Review + Create"

![Creating-Azure-Part1c](https://github.com/user-attachments/assets/4b253bbc-ce0c-46df-8eac-fbf8187f9562)

  - If everything looks good to you, then select "Create."

![Creating-Azure-Part1d](https://github.com/user-attachments/assets/949d869f-5867-43b1-a243-1ba378a3f994)

<h2>Step 2 - Create the Windows 10 Virtual Machine</h2>

- Search Virtual Machines and then select Virtual Machine
- Once you're on the VM page, select "Create" and then select "Virtual Machines."

![Creating-Azure-Part2a](https://github.com/user-attachments/assets/d79c9081-f3af-4780-8c94-aecdacf02bc9)

  - Select our resource group that we created
  - Name your VM

![Creating-Azure-Part2b](https://github.com/user-attachments/assets/1b58f672-d20f-435a-8854-6a12ff21521e)

  - Select a Zone
  - For your Image, select Windows 10 Pro for your operating system.
  - For size, select an option with "2 vCPUs." The reason for this is to prevent your VM from running slowly and clunkily.

![Creating-Azure-Part2c](https://github.com/user-attachments/assets/b997f4aa-d59b-4a6f-8fc3-95d143fb104d)

  - Create a Username & Password
  - Make sure to select Licensing
  - Select "Review + create"

![Creating-Azure-Part2d](https://github.com/user-attachments/assets/7e984696-a66e-44d1-b39b-9aae13d4c302)

  - Review to make sure everything looks correct, and then select "Create."

![Creating-Azure-Part2e](https://github.com/user-attachments/assets/bd4e5f77-6eed-4c5d-9930-95e7b5516680)

  - This process will take a couple of minutes to create the VM

<h2>Step 3 - Create a Linux VM</h2>

  - We will repeat mostly the same process as step 2, with some exceptions
  - Create another VM
  - Make sure your resource group is the same as the Windows VM
  - Name the Linux Machine
  - Select Ubuntu Server

![Creating-Azure-Part3a](https://github.com/user-attachments/assets/3a7f7148-5e51-44a5-bc81-65c7faf5e52b)

  - Select "Password" for Authentication type. Azure defaults to SSH public key.
  - Select a username and password.
  - Select "Next" and get to Networking

![Creating-Azure-Part3b](https://github.com/user-attachments/assets/7a1d0698-7e74-4f52-9941-c0757dc25468)

  - Make sure your Virtual Network is the same as your Windows

![Creating-Azure-Part3c](https://github.com/user-attachments/assets/9b8999ca-69ab-4f8a-8d68-682a07921c5c)

  - Leave everything as default and select "review and create" and "Create."

![Creating-Azure-Part3d](https://github.com/user-attachments/assets/56278c5d-bdfd-41f8-b3aa-aa2bc7d8b736)

  - Give it a few minutes, and it will complete

![Creating-Azure-Part3e](https://github.com/user-attachments/assets/f4df4b67-1c41-45b3-96f3-5b048aec79a1)

  - Head back to Resource Groups and you can click into your resource group that you have created, and can see your VMs you just created

![Creating-Azure-Part3f](https://github.com/user-attachments/assets/8d61580f-2be4-4985-a472-c00375e28101)
![Creating-Azure-Part3g](https://github.com/user-attachments/assets/c5fe4f42-aa2d-4fe6-87e6-38724b5b86f6)

  - I would make sure to go into your VMs and make sure they are on "Stop" if you don't plan on using them right away, so you are not charged for them while you're not using them.
  - If you are going to use them right away, you can either turn them on or leave them on

![Creating-Azure-Part3h](https://github.com/user-attachments/assets/8a9f86d2-d940-4929-9f56-f1923edc0d90)

<h2>Conclusion</h2>

This concludes our project. We successfully created a Resource Group, a Windows VM running Windows 10 Pro, and a Linux VM running Ubuntu in the Cloud. I look forward to using this VM for our next lab, so I would recommend keeping this one and not deleting it. 
