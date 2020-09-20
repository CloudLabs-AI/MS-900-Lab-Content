# MS-900

# Module 5: M365 Security and Compliance 

# Exercise 1: Azure AD Security 

### Task 1: Enable MFA in AAD using Conditional Access Policy 

1. Open a new browser window and login to the admin center at [https://admin.microsoft.com](https://go.microsoft.com/fwlink/p/?linkid=2024339).

1. When prompted, use the credentials provided in the **Environment Details** page to log in to the admin center.

1. From  the navigation menu scroll down to  **Admin centers** and select **Azure Active Directory**, the Azure Active Directory overview page will appear.

1. On the left side of the page scroll down to the **Security group**, then click **Conditional access**.

1. At the top of the Policies pane, click **+ New Policy**. 

1. Under Assignments, select **Users and groups**. Under Include, select **All users** and click on **Done**.

1. Under **Cloud apps**, click on **Select Apps** and select the apps for which you intend to apply policy.

1. Now under **Access controls** select **Grant**, and then select **Grant access**, check the **Require multi-factor authentication** checkbox, and click on **select**.

1. Confirm your settings and set Enable policy to **On**.

1. Click on **Create** to create and enable your policy.

### Task 2 : Azure AD PIM                                                                                                                                                                               
1. Privileged Identity Management (PIM) is a service in Azure Active Directory (Azure AD) that enables you to manage, control, and monitor access to important resources in your organization. These resources include resources in Azure AD, Azure, and other Microsoft Online Services such as Microsoft 365 or Microsoft Intune.

1. From  the navigation menu scroll down to  **Admin centers** and select **Azure Active Directory**, the Azure Active Directory overview page will appear.

1. In Azure Active Directory page click on **All services**  and select **Azure AD Privileged Identity Management**.

1. Under **Manage** select **Azure AD roles**. 

1. Now select **Settings**, from here you can configure role settings. Explore through the roles and select the role whose settings you want to configure.

1. Select **Edit** to open the Role settings page. On the Role setting page for each role, there are several settings you can configure.

1. Use the **Activation maximum duration** slider to set the maximum time, in hours, that a role stays active before it expires. This value can be from 1 to 24 hours.

1. To require multi-factor authentication before activation, check the Require Multi-Factor Authentication on activation box in the Assignment tab of Edit role setting.

1. **Requires approval to activate** Specifies whether a member of the Privileged Role Administrators or Security Administrators group is required to approve the activation.

1. Now select **Assignment**, from here you can choose one of these eligible assignment duration options.

1. Select **Notification**, from here we can configure to receive notification when a member is assigned as eligible to role or when a role is activated.

1. Now to assign a role, within **Azure AD Privileged Identity Management** page under manage, click on **Roles**. This displays list of roles for Azure AD permissions.

1. Select **Add assignments** to open the Add assignments page.

1. From **Select role** drop down select a role you want to assign, and under **Select  members** select a member to whom you want to assign   the role, and then select **Next**.

1. In the **Assignment type** list on the **Membership settings** pane, select **Eligible** or **Active**.

     -  **Eligible assignments** require the member of the role to perform an action to use the role. Actions might include performing a multi-factor authentication (MFA) check, providing a business justification, or requesting approval from designated approvers.

     -  **Active assignments** don't require the member to perform any action to use the role. Members assigned as active have the privileges assigned to the role at all times.

1. To specify a specific assignment duration, add a start and end date and time boxes. When finished, select **Assign** to create the new role assignment.

1. After the role is assigned, an assignment status notification is displayed.

1. Now select **Assignments** from here you can check **Eligible**, **Active** and **Expired** assignments. You can also add new assignments from here.

# Exercise 2: Threat Protection 

### Task 1 : Explore MS threat protection portal 

### Task 2 : Microsoft Secure Score 

1. Microsoft Secure Score is a measurement of an organization's security posture, with a higher number indicating more improvement actions taken. Following the Secure Score recommendations can protect your organization from threats. From a centralized dashboard in the Microsoft 365 security center, organizations can monitor and work on the security of their Microsoft 365 identities, data, apps, devices, and infrastructure.

1. From the **App launcher** click on All apps and in the search bar search for **Security**, from **Open context menu** click on Open in new tab. This will redirect you to the **Microsoft 365 security** web page.

1. Select **Secure Score** from the left hand menu. In the **Overview** page your score will be shown as a percentage, along with the number of points you've achieved out of a total possible points.

1. Additionally, if you select the Include button next to your score, you can choose different views of your score.

    - **Planned score** : Shows projected score when planned actions are completed.
    
    - **Current license score** : Shows score that can be achieved with your current Microsoft license.
    
    - **Achievable score**: Shows score that can be achieved with your Microsoft licenses and current risk acceptance.
    
1. Now select **Improvement actions** tab, this lists the security recommendations that address possible attack surfaces. It also includes their status (to address, planned, risk accepted, resolved through third party, resolved through alternate mitigation, and completed).

1. When you select a specific improvement action, a full page flyout appears.

   - **Manage** : Select Manage to go to the configuration screen and make the change. You'll then gain the points that the action is worth, visible in the fly out.
   
   - **Share** : Select Share to copy the direct link to the improvement action. You can also choose the platform to share the link, such as email, Microsoft Teams, Microsoft Planner, or ServiceNow. 

# Exercise 3: Cloud App Security 

### Task 1 : Discover Apps with Cloud App Security  

1. Microsoft Cloud App Security is a multimode Cloud Access Security Broker (CASB). It provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyberthreats across all your cloud services.

1. 
