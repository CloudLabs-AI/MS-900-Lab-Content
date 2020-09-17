# MS-900

# Module 5: M365 Security and Compliance 

# Exercise 1: Azure AD Security 

### Task 1: Enable MFA in AAD using Conditional Access Policy 

1. Open a new browser window and login to the admin center at [https://admin.microsoft.com](https://go.microsoft.com/fwlink/p/?linkid=2024339).

1. When prompted, use the credentials provided in the **Environment Details** page to log in to the admin center.

1. From  the navigation menu scroll down to  **Admin centers** and select **Azure Active Directory**, the Azure Active Directory overview page will appear.

1. On the left side of the page scroll down to the **Security group**, then click **Conditional access**.

1. At the top of the Policies pane, click **+ New Policy**. 

1. Under Assignments, select **Users and groups**. Under Include, select **All users** and then select **Done**.

1. Under **Cloud apps**  click on **Select Apps** and select the apps for which you intend to apply policy.

1. Now under **Access controls** select **Grant**, and then select **Grant access**, click the **Require multi-factor authentication** checkbox, and click on **select**.

1. Confirm your settings and set Enable policy to **On**.

1. Select **Create** to create and enable your policy.

### Task 2 : Azure AD PIM                                                                                                                                                                               
