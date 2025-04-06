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
3. Click **+ Add a group**.
4. Choose **Microsoft 365** as the group type and click **Next**.
5. Enter:
   - **Group name** (e.g., "Marketing Team")
   - **Group email address**
   - **Description**
   - **Privacy** (Public or Private)
6. Enable options like team creation and group management if needed.
7. Add owners and members.
8. Click **Create**, then **Close**.

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
