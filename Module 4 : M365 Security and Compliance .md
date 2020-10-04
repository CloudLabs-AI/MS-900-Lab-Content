# MS-900

# Module 4 : M365 Security and Compliance 

  This module helps you to understand various features that contribute towards overall organization security.

# Exercise 1: Azure AD Security 

  In this exercise you will understand how to enable MFA in Azure Active Directory. Then Configure and manage access to important resources using Azure AD PIM.
  
### Task 1: Enable MFA in AAD using Conditional Access Policy 

1. Open a new browser window and login to the admin center at [https://admin.microsoft.com](https://go.microsoft.com/fwlink/p/?linkid=2024339).

1. When prompted, use the credentials provided in the **Environment Details** page to log in to the admin center.

1. From  the navigation menu scroll down to  **Admin centers** and select **Azure Active Directory**, the Azure Active Directory overview page will appear.

   ![](Images/img116.png)

1. On the left side of the page scroll down to the **Security**.

   ![](Images/img127.png)

1. In the **Security** page select **Conditional access**.

   ![](Images/img128.png)

1. At the top of the Policies pane, click **+ New Policy**. 

   ![](Images/img142.png)

1. Provide a name for your policy. Under Assignments, select **Users and groups**. In Include tab, select **Users and groups**. In the search bar search  and select the user's you intend to enable MFA and click on **Select**.

   ![](Images/img135.png)

1. Under **Cloud apps**, click on **Select Apps** and select the apps for which you intend to apply policy.

   ![](Images/img136.png)

1. Now under **Access controls** select **Grant**, and then select **Grant access**, check the **Require multi-factor authentication** checkbox, and click on **select**.

   ![](Images/img137.png)

1. Now in Conditions tab select **Client apps** and in **Client apps** page under **Configure** select **Yes** and then select **Done**. You can also make use of other conditions like risk, device platform, or location based on your requirement.

   ![](Images/img138.png)

1. Confirm your settings and set Enable policy to **On**. Click on **Create** to create and enable your policy.

   ![](Images/img139.png)

1. Now to test the policy login to the user admin account for whom you enabled MFA. From **App launcher** under Apps, select the app for which you enabled MFA.

1. You're required to register for and use Azure Multi-Factor Authentication. In more information required page click **Next**.

1. Follow the prompts to complete the process and verify you successfully sign in to the portal.

   ![](Images/img140.png)
   
   ![](Images/img141.png)
   
1. To learn more about conditional access and policies refer to https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/overview.

### Task 2 : Azure AD PIM                                                                                                                                                                               
1. Privileged Identity Management (PIM) is a service in Azure Active Directory (Azure AD) that enables you to manage, control, and monitor access to important resources in your organization. These resources include resources in Azure AD, Azure, and other Microsoft Online Services such as Microsoft 365 or Microsoft Intune.

1. From  the navigation menu scroll down to  **Admin centers** and select **Azure Active Directory**, the Azure Active Directory overview page will appear.

   ![](Images/img116.png)
   
1. In Azure Active Directory page click on **All services**  and select **Azure AD Privileged Identity Management**.

1. Under **Manage** select **Azure AD roles**. 

   ![](Images/img117.png)

1. Now select **Settings**, from here you can configure role settings. Explore through the roles and select the role which you want to configure.

   ![](Images/img118.png)

1. Select **Edit** to open the Role settings page. On the Role setting page for each role, there are several settings you can configure.

   ![](Images/img119.png)

1. Use the **Activation maximum duration** slider to set the maximum time, in hours, that a role stays active before it expires. This value can be from 1 to 24 hours.

   ![](Images/img120.png)

1. To require multi-factor authentication before activation, check the Require Multi-Factor Authentication on activation box in the Assignment tab of Edit role setting.

1. **Requires approval to activate** Specifies whether a member of the Privileged Role Administrators or Security Administrators group is required to approve the activation.

1. Now select **Assignment**, from here you can choose one of these eligible assignment duration options.

   ![](Images/img121.png)

1. Select **Notification**, from here we can configure to receive notification when a member is assigned as eligible to role or when a role is activated.

   ![](Images/img122.png)

1. Now to assign a role, within **Azure AD Privileged Identity Management** page under manage, click on **Roles**. This displays list of roles for Azure AD permissions.

1. Select **Add assignments** to open the Add assignments page.

   ![](Images/img123.png)

1. From **Select role** drop down select a role you want to assign, and under **Select  members** select a member to whom you want to assign   the role, and then select **Next**.
   
   ![](Images/img124.png)

1. In the **Assignment type** list on the **Membership settings** pane, select **Eligible** or **Active**.

     -  **Eligible assignments** require the member of the role to perform an action to use the role. Actions might include performing a multi-factor authentication (MFA) check, providing a business justification, or requesting approval from designated approvers.

     -  **Active assignments** don't require the member to perform any action to use the role. Members assigned as active have the privileges assigned to the role at all times.
     

1. To specify a specific assignment duration, add a start and end date and time boxes. When finished, select **Assign** to create the new role assignment.

   ![](Images/img125.png)

1. After the role is assigned, an assignment status notification is displayed.

1. Now select **Assignments** from here you can check **Eligible**, **Active** and **Expired** assignments. You can also add new assignments from here.

   ![](Images/img126.png)
   
 1. You can learn more about Priviliged identity management by refering to https://docs.microsoft.com/en-us/azure/active-directory/privileged-identity-management/pim-configure.

# Exercise 2: Threat Protection 

  In this exercise you will explore through Microsoft threat protection portal and Microsoft Secure Score.

### Task 1 : Explore MS threat protection portal 

1. Microsoft Threat Protection is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and applications to provide integrated protection against sophisticated attacks.

1. The Microsoft 365 security center provides security administrators and other risk management professionals with a centralized hub and specialized workspace that enables them to manage and take full advantage of Microsoft 365 intelligent security solutions for identity and access management, threat protection, information protection, and security management.

1. From the **App launcher** click on All apps and in the search bar search for **Security**, from **Open context menu** click on Open in new tab. This will redirect you to the **Microsoft 365 security** web page.

1. The home page provides  at-a-glance view of the overall security health of your organization.

   ![](Images/img238.png)

1.  From the left navigation menu select **Alerts**. Alerts provides greater visibility on all Microsoft 365 environments, that includes alerts from Microsoft Cloud App Security, Office 365 ATP, Azure AD, Azure ATP, and Microsoft Defender ATP. 

    ![](Images/img240.png)

1. Select **Reports** from here you can view security trends and track the protection status of your identities, data, devices, apps, and infrastructure.

   ![](Images/img241.png)

1. Select **Secure Score** this page provides an all up summary of the different security features and capabilities you've enabled and includes recommendations for areas to improve.

   ![](Images/img112.png)

1. Now select **Classification**, from here you can set labels. When a label is applied (automatically or by the user), the content or site is protected based on the settings you choose.

1. Select **Policies**  from here you can set up policies to manage devices, protect against threats, and receive alerts about various activities in your organization.

1. Select **Permissions**. You can manage who in your organization has access to view content and perform tasks in the Microsoft 365 security center.

   ![](Images/img243.png)
   
1. To learn more about Threat Protection refer to https://docs.microsoft.com/en-us/microsoft-365/security/mtp.

### Task 2 : Microsoft Secure Score 

1. Microsoft Secure Score is a measurement of an organization's security posture, with a higher number indicating more improvement actions taken. Following the Secure Score recommendations can protect your organization from threats. From a centralized dashboard in the Microsoft 365 security center, organizations can monitor and work on the security of their Microsoft 365 identities, data, apps, devices, and infrastructure.

1. From the **App launcher** click on All apps and in the search bar search for **Security**, from **Open context menu** click on Open in new tab. This will redirect you to the **Microsoft 365 security** web page.

1. Select **Secure Score** from the left hand menu. In the **Overview** page your score will be shown as a percentage, along with the number of points you've achieved out of a total possible points.

   ![](Images/img112.png)

1. Additionally, if you select the Include button next to your score, you can choose different views of your score.

    - **Planned score** : Shows projected score when planned actions are completed.
    
    - **Current license score** : Shows score that can be achieved with your current Microsoft license.
    
    - **Achievable score**: Shows score that can be achieved with your Microsoft licenses and current risk acceptance.
    
       ![](Images/img113.png)
    
1. Now select **Improvement actions** tab, this lists the security recommendations that address possible attack surfaces. It also includes their status (to address, planned, risk accepted, resolved through third party, resolved through alternate mitigation, and completed).

   ![](Images/img114.png)

1. When you select a specific improvement action, a full page flyout appears.

   - **Manage** : Select Manage to go to the configuration screen and make the change. You'll then gain the points that the action is worth, visible in the fly out.
   
   - **Share** : Select Share to copy the direct link to the improvement action. You can also choose the platform to share the link, such as email, Microsoft Teams, Microsoft Planner, or ServiceNow. 
   
       ![](Images/img115.png)
 
 1. To learn more about secure score refer https://docs.microsoft.com/en-us/microsoft-365/security/mtp/microsoft-secure-score?view=o365-worldwide.
       
# Exercise 3: Cloud App Security 

  In this exercise you will use the  Cloud App Security portal to identiify the senstivity and criticality of data and apps owned by an organization and address them.

### Task 1 : Discover Apps with Cloud App Security  

1. Microsoft Cloud App Security is a multimode Cloud Access Security Broker (CASB). It provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyberthreats across all your cloud services.

1. In the **admin center**, from the **App launcher** click on **All apps** and in the search bar search for **Security**, from Open context menu click on **Open in new tab**.

   ![](Images/img178.png)

1. In the Microsoft 365 security page, click **More resources**, and then select **Cloud App Security**.

   ![](Images/img179.png)

1. From the left hand menu select **Dashboard**. In dashboard you can see details about:

   - **Open alerts** : Shows the number of open alerts, a graph of the alert status distribution, and recent alerts

   - **Discovered apps** :Shows the number of discovered apps, a graph of the app risk distribution, and the top app categories by traffic.

   - **Top users to investigate** :Shows the number of users to investigate and the users with the highest investigation priority.

   - **Conditional Access App Control** : Shows the number of apps protected by Conditional Access App Control as well as the number of protected sessions and actions over the last 30 days.
   
   - **App connectors status** : Shows the number of API connected app instances and their status.

   - **Files infected with malware** : Shows the number of files infected with malware.

   - **Privileged Office 365 OAuth apps** : Shows the number of rarely used OAuth apps granted highly privileged permissions.

   - **Azure security configuration** : Shows the number and severity of Azure security configuration recommendations.
   
     ![](Images/img180.png)

1. Now from left navigation menu select **Discover**. Cloud Discovery uses your traffic logs to dynamically discover and analyze the cloud apps that your organization is using.

1. Under **Discover** select **Create snapshot report**. 
   
   ![](Images/img181.png)

1. Collect log files from your firewall and proxy, through which users in your organization access the Internet. Make sure to gather logs during times of peak traffic that are representative of all user activity in your organization.

1. If you don't have a log file follow the below steps to download a sample log file.

1. Enter a **Report name** and a **Description**. Select the **Data source** from which you want to upload the log files. Click **View and verify** then Download sample.

   ![](Images/img182.png)
   
   ![](Images/img183.png)

1. In **Choose traffic logs** browse and upload the log file which you downloaded. Click **Create**.

1. After upload completes, the status message will appear at the top right corner of your screen letting you know that your log was successfully uploaded.

1. After you upload your log files, it will take some time for them to be parsed and analyzed. Wait till the status of your log files turns **Ready**.

   ![](Images/img184.png)

1. Now from the left hand menu under **Discover** select **Cloud Discovery Dashboard**. It provides an at-a-glance overview of what kinds of apps are being used, your open alerts, and the risk levels of apps in your organization. It also shows you who your top app users are and provides an App Headquarter location map.

   ![](Images/img185.png)
   
   ![](Images/img186.png)

1. Click on **Discoverd apps** tab, from here you can review which apps are risky and which are commonly used by using filters like:

    - **App tag** : Tags enable you to customize the Cloud App Catalog. You can select from either Sanctioned, Unsanctioned, or create custom tags for apps. These tags can then be used as filters.
    
    - **Risk score** : Lets you filter apps by risk score that you can focus on. For example, reviewing only risky apps.
    
    - **Compliance risk factor** : Lets you search for a specific standards, certification, and compliance that the app may comply with.
    
    - **Security risk factor** : Enables you to filter based on specific security measures (such as Encryption at rest, multi-factor authentication, etc.).
    
    - **Apps and domains** : Enables you to search for specific apps or apps used in specific domains.
    
    - **Categories** : The categories filter, located on the left of the page, enables you to search for types of apps according to app categories.
    
    - **Usage** : Lets you filter based on the usage statistics of this app. Usage such as apps with less than or more than a specified number of data uploads, apps with more than or less than a specified number of Users.
    
    - **Legal risk factor** : Lets you filter based on all the regulations and policies that are in-place to ensure data protection and privacy of the app's users.
    
      ![](Images/img187.png)
    
1. Explore through other **IP address** and **Users** tab.

1. From the left hand pane select **Alerts**. Alerts are the entry points to understanding your cloud environment more deeply.

1. In the Alerts page, select Open for the **Resolution Status**. This section of the dashboard provides full visibility into any suspicious activity or violation of your established policies. It can help you safeguard the security posture you defined for your cloud environment.

   ![](Images/img188.png)

1. For each alert, you need to investigate and determine the nature of the violation and the required response. You can filter the alerts by **Alert type**, by **Severity**, by **App** or by **User Name** to process the most important ones first.
    
      ![](Images/img189.png)
    
 1. You can also customize alerts and actions by creating policies. In alerts page click on **Create policy**. Select **App discovery policy**. Based on your requirement you can choose other **policies**.
 
    ![](Images/img190.png)
 
 1. Give your policy a name and description. If you want, you can base it on a template. Set the severity of the policy.
 
    ![](Images/img191.png)
 
 1. To set which discovered apps trigger this policy, click **+** add filters. From the dropdown select the filter based on your requiremnet.
 
    ![](Images/img192.png)
 
 1. Enable **Trigger a policy match if all the following occur on the same day**. Select criteria from the drop down based on your requirements.
 
    ![](Images/img193.png)
 
 1. Set a **Daily alert limit** under Alerts. Select whether the alert is sent as an email, a text message, or both. 
 
    ![](Images/img194.png)
 
 1. Select **Governance actions** to apply when an app matches this policy. It can tag policies as **Sanctioned**, **Unsanctioned**, or a custom tag. Click **Create**. 
 
    ![](Images/img195.png)
 
 1. Alert will be triggered whenever an app with your specified conditions meet, notification will be sent to the email or number specified.
 
 1. To learn more about Cloud App Security refer https://docs.microsoft.com/en-us/cloud-app-security.
 
### Exercise 4 : Information Protection 

  In this exercise you will learn how to classify and protect your organization's data using sensitivity label.

### Task 1 : Setup Data sensitivity label and policy 

1. Sensitivity labels from the Microsoft Information Protection framework let you classify and protect your organization's data, while making sure that user productivity and their ability to collaborate isn't hindered.

1. In the **admin center**, from  the navigation menu scroll down to  **Admin centers** and select **Compliance**, the Microsoft 365 Compliance center overview page will appear.

   ![](Images/img89.png)

1. Now under **Solutions** select **Information protection**. If you don't immediately see this option, first select **Show all**.

1. On the **Labels** page, select **+ Create a label** to start the New sensitivity label wizard.

   ![](Images/img90.png)

1. Enter a **Label name**  and **Description**. Select **Next**.

   ![](Images/img91.png)

1. In **Encryption** page, choose when you want to assign permissions, whether you want your users' access to the content to expire, and whether you want to allow offline access. 

      - **Encryption** : select Apply.
      
      - **Assign permissions now or let users decide?** : select Assign permissions now.
      
      - **User access to content expires** : select On a specific date. You can also select other options based on requirement.
      
      - **Acess expires** : Select a date. After this time, users won't be able to open the labeled item.
      
      - **Allow offline access** :  Never, always, or for a specific number of days after the label is applied. If you restrict offline access to never or a number of days, when that threshold is reached, users must be reauthenticated and their access is logged. 
      
         ![](Images/img92.png)
      
1. Under **Assign permissions to specific users or groups** click on **Assign permissions**. From here you can grant permissions to specific people so that only they can interact with the labeled content.
 
1. In **Assign permissions** pane, add users or groups that will be assigned permissions to the labeled content. For now select **+ Add users or groups** and select the user or group for whom you want to assign the label. Select **Add**.

   ![](Images/img93.png)
 
1. Now in **Assign permissions** pane, click on **Choose permissions**. 

   ![](Images/img95.png)

1. When you choose which permissions to allow for those users or groups, you can select either a predefined permissions level with a preset group of rights, such as Co-Author, CO-Owner, Reviewer or Viewer and Custom permissions, where you choose one or more usage rights.

   ![](Images/img96.png)
   
1. On the **Assign Permissions** pane, select **Save**. Click on **Next**.

   ![](Images/img97.png)

1. On the **Content Marking** page, you can configure the Header, Footer and the Water Marking for this label. Click Next.

   ![](Images/img98.png)
   
   ![](Images/img99.png)

1. In **Auto-labeling for Office apps**, turn on **Auto labeling**. Add a condition, under **Detect content that matches these conditions**, select Add a condition. 

   ![](Images/img100.png)
   
   ![](Images/img101.png)

1. Select **Next**. Review your settings, and select **Create**. Your label will be created. Repeat this process for any additional labels you want.

   ![](Images/img102.png)

1. Click on your newly created label from here you can edit, publish or delete it.

   ![](Images/img103.png)

1. Now click on **Label policies** and select **Publish labels**. 

   ![](Images/img104.png)

1. On the next page Click  **Choose sensitivity labels to publish**, and select your newly created label and click **ADD**  and then click **Next**.

   ![](Images/img105.png)
   
   ![](Images/img107.png)

1. In **Publish to users and groups** pane select the **Users and Groups** and click on **Add**. Now select users or groups which you are going to publish this label and Click **Next** to continue.
   
   ![](Images/img108.png)

1. Under the **Policy Setting**, select the way you prefer and click **Next**.

   ![](Images/img109.png)

1. Provide Name and Description for your policy. Click **Next**.

   ![](Images/img110.png)

1. Click **Submit** to finish the policy creation for the label.

   ![](Images/img111.png)
   
1. In order for your labels to work, each user needs to download the Azure Information Protection unified labeling client. Search the web for **AzinfoProtection_UL.exe**, then download it from the Microsoft Download Center, and run it on your users' computers.

1. The next time you open an Office app like Word, you'll see the sensitivity labels that were created. 

   ![](Images/img245.png)

1. Learn more about Sensitivity lables by refering  https://docs.microsoft.com/en-us/microsoft-365/compliance/sensitivity-labels?view=o365-worldwide#:~:text=Unlike%20retention%20labels%2C%20which%20are,and%20groups%20see%20the%20labels.

### Exercise 5 : Compliance Manager 

  This exercise will let you explore through the features of Compliance Manager and Customer LockBox.

### Task 1 : Explore Compliance Manager 

1. Compliance Manager measures your progress in completing actions that help reduce risks around data protection and regulatory standards.

1. In the **admin center**, from  the navigation menu scroll down to  **Admin centers** and select **Compliance**, the Microsoft 365 Compliance center overview page will appear.

   ![](Images/img89.png)

1. From the left navigation pane select **Compliance Manager**. In the overview page you can see your overall Compliance score, Compliance score breakdown.

   ![](Images/img143.png)

1. In the **Compliance Manager** page, select **Improvement action**. This displays the list of actions you can take to improve your compliance score. Each improvement action provides recommended guidance that’s intended to help you align with data protection regulations and standards.

   ![](Images/img144.png)

1. In the **Compliance Manager** page, select **Solutions** tab. The solutions page displays your organization’s solutions that are connected to improvement actions. The table lists each solution’s contribution to your overall score, the points achieved and possible within that solution, and the remaining number of improvement actions grouped in that solution that can increase your score.

   ![](Images/img145.png)

1. On the row of your intended solution, under the Remaining actions column, select the hyperlinked number. You’ll see a filtered view of the improvement actions screen showing untested improvement actions for that solution.

   ![](Images/img146.png)

1. On the row of your intended solution, under the Open solution column, select Open. You’ll see the solution or location in the Microsoft 365 and Office 365 security and compliance centers where you can take the recommended action.

   ![](Images/img147.png)
   
1. Now in the **Compliance Manager** page select **Assessments**. Assessments help us to implement data protection controls specified by compliance, security, privacy, and data protection standards, regulations, and laws. 

1. The assessments page summarizes key information about each assessment:

      - **Status** : Complete, Incomplete, None or In progress.
      
      - **Assessment progress**: the percentage of the work done toward completion, as measured by the number of controls successfully tested.
      
      - **Your improvement actions**: the number of completed actions to satisfy implementation of your controls.
      
      - **Microsoft actions**: the number of completed actions to satisfy implementation of Microsoft controls.
      
      - **Group**: name of the group the assessment belongs to.
      
      - **Product**: associated Microsoft 365 service.
      
      - **Regulation**: the regulatory standard, policy, or law that applies to the assessment.
      
         ![](Images/img148.png)

1. In the **Assessments** dashboard, select the assessment name to open it and view the Action Items and Controls Info.

1. To learn more about Compliance manager refer https://docs.microsoft.com/en-us/microsoft-365/compliance/compliance-manager-setup?view=o365-worldwide.

### Task 2 : Customer Lockbox 

1. Customer Lockbox ensures that Microsoft cannot access your content to perform a service operation without your explicit approval. Customer Lockbox brings you into the approval workflow for requests to access your content.

1. In the **admin center**, from  the navigation menu scroll down to  **Settings** and select **Org settings**.

1. Select **Services** in the search bar search and select  **Customer Lockbox**.

   ![](Images/img86.png)

1. Now enable the setting **Require approval for all data access requests**.

   ![](Images/img88.png)

1. To approve or deny requests, head over to the Office 365 admin center and under **Support** select **Customer Lockbox requests**. User with Global Admin role and Customer Lockbox access approver role can approve or deny requests.

   ![](Images/img87.png)
   
1. To learn more about Customer LockBo refer https://docs.microsoft.com/en-us/microsoft-365/compliance/customer-lockbox-requests?view=o365-worldwide.

## Conclusion

 In this module you learnt to use Microsoft Security and Compliance features to secure your organization's data, information and applications.

      
