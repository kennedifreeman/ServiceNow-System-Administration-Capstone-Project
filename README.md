
<h1>ServiceNow System Administrator Capstone Project</h1>

<h2>Description</h2>
Capstone project focused on hands-on experience with ServiceNow platform. I performed key system administrative tasks, including table creation, data imports, form and view customization and configuration, and platform configuration.
<br />

<h2>Project Highlights</h2>

<b> 
> Platform: ServiceNow
> Skills Practiced: User account creation, password resets, OU management, account deactivation <br> 
> Tools Used: ServiceNow Studio, Import Sets, Tables & Columns, Forms & Views <br>
> Difficulty Level: 🟠 Intermediate  <br>
> Real-World Relevance: Simulates common ServiceNow administrator tasks such as configuring tables, forms, and lists, managing records, and customizing and configuring the platform for organizational needs <br>
</b>

<h2>Program walk-through:</h2>

<p align="center">
🛠 Step 1: Accessing Active Directory Users and Computers <br/>
<p align="left">
After logging into the Server Academy lab environment:
 1. Click the tart menu.<br>
2. Open server manager.<br>
3. In the top right corner, click TOOLS.<br>
4. From the dropdown menu, select active directory users and computers.<br>

This opens the ADUC console, which is where all user, group, and OU management is performed.  

<br />
<br />
<p align="center">
👤 Step 2 – Creating New User Accounts  <br/>
<p align="left">
1.  In ADUC, navigate to the domain name listed in the left-hand panel. <br>
2. Right-click the organizational unit (OU) where the user should be created (e.g., Domain Admin Users). <br> 
3. Select NEW → USER.  <br>
4. 📝 Enter:  <br>
   - First Name  <br>
   - Last Name  <br>
   - User Logon Name (e.g., `jane.doe@sdcsm.com`)  <br>
5. Set an initial password.  <br>
6. Check user must change password at next logon. <br> 
7. Click finish to create the account.  <br>

<br />
<br />
<p align="center">
🔄 Step 3 – Resetting Passwords: <br/>
<p align="left">
1. Locate the user in the correct OU. <br>
2. Right-click their name and select reset password. <br> 
3. Enter a new temporary password.  <br>
4. Check **User must change password at next logon**. <br>
5. Click ok. <br>
 
<br />
<br />
<p align="center">
🔀 Step 4 – Moving Users Between OUs:  <br/>
<p align="left">
1. Select the user account in the left-hand panel. <br>
2. Drag the user into the new OU (e.g., from Domain Admin Users to Domain Users).  <br>
3. Click yes to confirm the move. <br>


<br />
<br />
<p align="center">
🚫 Step 5 – Disabling and Deleting Accounts:  <br/>
<p align="left">
To Disable: 
1. Right-click the user account. <br>
2. Select disable account (a down arrow icon appears on the user icon). <br>
To Delete:  
1. Right-click the user account. <br>
2. Select Delete. <br>
3. Confirm the deletion. <br>

<br />
<br />
<h2>Key Takeaways:</h2>
  📌 Key Takeaways <br>
- 📂 Accessing ADUC requires going through Server Manager → Tools → Active Directory Users and Computers**. <br> 
- 🗂 Keeping a clear **OU hierarchy** makes user management far easier. <br>
- 🔐 Always force password changes after a reset to maintain security. <br>
- 🚫 Disabling accounts is a safer first step before deleting. <br>


 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
