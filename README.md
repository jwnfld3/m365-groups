# Set Up Microsoft 365 Groups and SharePoint Site Management

## Overview
This lab guides the process of creating and managing **Microsoft 365 Groups** and **SharePoint Sites** for seamless collaboration and document management. Admins will configure policies, permissions, and site settings, helping ensure effective and secure teamwork across the organization.

---

## Who
Admins responsible for managing Microsoft 365 Groups and SharePoint sites.

## What
- Create Microsoft 365 Groups for collaboration across Outlook, Teams, and SharePoint.
- Set up SharePoint Sites linked to groups for centralized file sharing and collaboration.

## When
After the Microsoft 365 tenant is set up and admin access to the Microsoft 365 Admin Center and SharePoint Admin Center is available.

## Where
- Microsoft 365 Admin Center
- SharePoint Admin Center

## Why
To facilitate collaboration and data management by integrating Microsoft 365 Groups with SharePoint sites for shared resources, files, and communication.

---

## Step-by-Step Instructions

### 1. Create a Microsoft 365 Group
1. Sign in at [admin.microsoft.com](https://admin.microsoft.com).
2. Navigate to **Groups > Active groups**.
![image](https://github.com/user-attachments/assets/1e40815b-c909-42b4-a4d2-146c66978c1a)

3. Click **+ Add a Microsoft 365 group**.
![image](https://github.com/user-attachments/assets/d21b1951-05d7-4723-a1bc-14225b240e02)

4. Enter:
   - **Group name** (e.g., "Marketing Team")
![image](https://github.com/user-attachments/assets/e9d38941-edee-4a95-92f1-c3293c6df9c1)
   - **Assign Owners**
![image](https://github.com/user-attachments/assets/717f2ad5-cdcc-4a90-ace2-2bc5ea5edab4)
   - **Add Members**
![image](https://github.com/user-attachments/assets/9a59e2a5-7997-4c25-a470-b46d9fd1f2f3)

    - **Group email address**
   - **Privacy** (Public or Private)
![image](https://github.com/user-attachments/assets/585f2225-657f-4cbd-8a84-5a3537d42b1f)

5. Click **Create group**
![image](https://github.com/user-attachments/assets/48d6a57a-9472-4824-bb7e-109671466ec1)
![image](https://github.com/user-attachments/assets/6c5f27b9-1aa0-4088-98a1-06372bb48773)

---

### 2. Create a SharePoint Site Associated with the Group
1. In Microsoft 365 Admin Center, go to **Admin centers > SharePoint**.
2. In the SharePoint Admin Center, click **Sites > Active sites**.
3. Click **+ Create > Team site**.
4. Enter:
   - **Site name** (e.g., "Marketing Team Site")
   - Confirm it links to the Microsoft 365 Group
   - Set **Privacy settings**
5. Configure:
   - **Storage quota**
   - **Language**
   - **Site classification**
6. Click **Finish** to create the site.

---

### 3. Set Site Permissions
1. In **Active sites**, select the newly created site.
2. Click **Permissions**.
3. Add/remove users and assign roles:
   - **Owner**
   - **Member**
   - **Visitor**
4. Choose access settings:
   - **Only members**
   - **Anyone with the link**

---

### 4. Customize SharePoint Site
1. Under the site homepage, go to **Site contents**.
2. Click **+ New** to add:
   - **Document Libraries**
   - **Lists**
3. Integrate with:
   - **Planner**
   - **Forms**
   - **Power Automate**
4. Customize branding:
   - Go to **Settings (gear icon) > Change the look**
   - Modify themes, colors, and logos

---

## Definitions

- **Microsoft 365 Groups**: A cross-app membership service connecting Outlook, Teams, SharePoint, and other services to enable collaboration with shared resources.
- **SharePoint Site**: A web-based platform to manage content, share documents, and collaborate with team members, often linked to a Microsoft 365 Group.

---

## Conclusion

Setting up Microsoft 365 Groups with SharePoint integration provides a powerful collaboration framework for modern organizations. By managing access, customizing sites, and enabling cross-app integration, administrators can create a secure and efficient environment that promotes teamwork and centralizes content management. This lab lays the foundation for scalable collaboration practices within Microsoft 365.
