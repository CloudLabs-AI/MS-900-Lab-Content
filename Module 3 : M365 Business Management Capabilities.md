# Module 3 : M365 Business Management Capabilities 

 In this module, you will learn to work with M365 groups, Microsoft Planner, Forms, Power BI. You will also explore through Microsoft Endpoint Manager.

# Exercise 1: Types of Groups in M365 

1. In the Groups section of the Microsoft 365 admin center, you can create and manage different types of groups:

   - **Microsoft 365 group**:  Microsoft 365 groups are used for collaboration between users, both inside and outside your company. With each Microsoft 365 group, members get a group email and shared workspace for conversations, files, and calendar events, and a Planner.
   
   - **Distribution**: Distribution groups are used for sending notifications to a group of people. They can receive an external email if enabled by the administrator.
   Distribution groups are best for situations where you need to broadcast information to a set group of people.
   
   - **mail-enabled security**: These groups are used for granting access to resources such as SharePoint, and emailing notifications to those users.
   
   - **Security groups**: They can be used for granting access to resources such as SharePoint sites. They can make administration easier because you need to only administer the group rather than adding users to each resource individually.
   
# Exercise 2: Create M365 Groups

  In this exercise, you will learn how to create groups and add members to it from the admin center.

### Task 1: Create Office 365 Groups

1. Open a new browser window and log in to the admin center at https://admin.microsoft.com.

1. When prompted, use the credentials provided in the **Environment Details** page to login to the admin center.

1. From the navigation menu click on the **Teams & Groups** icon and click on **Active teams & groups**, now select **Add a group** icon.

   ![](Images/image02.png)
    
1. On the Choose a group type page, select **Microsoft 365**, and click on **Next**.

   ![](Images/M3E2T1Step401.png)

1. On the Basics page, type a name for the group as **Sales-demo** and a description(optional). Click **Next**.

   ![](Images/M3E2T1Step501.png)   

1. On the **Owners** page, choose the name of one or more people who will be designated to manage the group. Anyone who is a group owner can add or remove members and have unique permissions like the ability to delete conversations from the shared inbox or change different settings about the group. Click **Next**.
 
   ![](Images/M3E2T1Step601.png) 
  
   ![](Images/M3E2T1Step6.101.png)  
  
   ![](Images/M3E2T1Step6.201.png)
   
1. Now in the **Members** page, you can join 20 member including owner, and then click **Next**.

   ![](Images/M3E2T1Step701.png) 
   
   ![](Images/M3E2T1Step7.101.png)
   
   ![](Images/M3E2T1Step7.201.png)

1. Now in the **Settings** page, type a unique email address for the group, choose a privacy option based on your requirement, and whether you want to add Microsoft Teams for the group, and then click **Next**.

   ![](Images/M3E2T1Step801.png)

1. Review your settings and make any changes if needed, select **Create group**, and then **close**.

   ![](Images/M3E2T1Step901.png)

1. In the admin center, select the name of the group that you want to add members to. Refresh the page if you are not able to see the newly created group.

1. To add members to the group, navigate to the **Members tab** and select **View all and manage members**.

   ![](Images/img59.png)
   
1. Click on **Add members**, select the users you want to add, and then click on **Save**.

   ![](Images/img60.png)
   
1. To learn more about groups refer to https://docs.microsoft.com/en-us/microsoft-365/admin/create-groups.

# Exercise 3: Explore Microsoft Planner 

Microsoft Planner provides a hub for team members to create plans, organize, and assign tasks to different users, and to check updates on progress through dashboards. It also provides a centralized place where files can be shared and give visibility to the whole team.

In this exercise, you will learn how to create a new plan in Microsoft Planner and add members to it, create buckets, add tasks to the bucket and assign the tasks to the user.

1. Open a new browser window and log in to the office365 center at https://www.office.com.

1. When prompted enter the username and password of the user which you have created in the the Exercise 1 task 1. For example Odl_User-DeploymentId. 

1. In the office365 portal from the App launcher click on **All apps** and in the search bar search for **Planner**, from **Open context menu** click on Open in new tab, this will redirect you to the **Planner** web page.

1. Select **New plan**  in the left pane.
 
   ![](Images/img61.png)

1. In the **New plan** window: 
    
    - Enter a name for the plan as **Demo-plan**
    
    - Make the plan public if you want it to be visible to the rest of your organization and in search results, or make it private if you want only plan members to see it.
    
    - Click on **Add to an existing Microsoft 365 Group** to create your plan in an existing group or if needed you can create a new group.
    
    - Select **Create plan**.
    
   ![](Images/img62.png)

1. Now to add members to the plan, from the upper-right corner of the Planner window click on **Members**.

   ![](Images/img63.png)

1. Search the name or email address of a person within your organization that you want to add to the plan and select the person's card when it appears.

1. Now to create a bucket click on **Add new bucket**. Buckets helps to organize tasks into things like workstreams, project phases, or topics. 

   ![](Images/img232.png)

1.  Type a name for the bucket, and then press Enter.

1. Select **Add task** below the heading of the bucket to which you want to add a task.
    
    - Provide a task name
    
    - Select a due date for the task
    
    - Click on **Assign** and choose a plan member from the list. If the right person isn't listed, type a name or email address in the search box to add someone new.
    
   ![](Images/img233.png)
 
1. Click on the task to open the task window. 
 
1. Select **Start anytime** below Start date, and then select the start date you want. Select **Due anytime** below Due date, and then select the due date you want.
 
   ![](Images/img234.png)
     
1. In the task window select **Priority**  from here you can set the priority of the task.
 
   ![](Images/img235.png)
 
1. Select **Add attachment**. Select **computer** to attach a locally stored file, select **Link** to include a link, or select **SharePoint** to attach a file from a SharePoint site.

   ![](Images/image10.png)

1. Navigate to and select the file you want to attach or enter the link information.

1. You can also add comments in **Comment** section. When done click on the dismiss button in the upper-right corner of the task window to save and close the task.

1. Now select **Charts**. The charts show how your plan is progressing, with details about what’s done, in progress, not started, and late.

   ![](Images/img237.png)

1. To learn more about planner refer to https://support.microsoft.com/en-us/planner.

# Exercise 4 : Setup Microsoft Forms 

This exercise explains how to create and work with Microsoft Forms.
 
### Task 1 : Creating a new Form

With Microsoft Forms, you can create surveys, quizzes, and polls, and easily see results as they come in.

In this task, you will learn how to create a Form using Microsoft Forms.

1. Open a new browser window and log in to the office365 center at https://www.office.com.

1. When prompted enter the username and password of the user which you have created in the the Exercise 1 task 1. For example Odl_User-DeploymentId. 

1. In the office365 portal from the **App launcher** click on **All apps** and in the search bar search for **Forms**, from **Open context menu** click on **Open in new tab**, this will redirect you to the **Forms** web page.

1. Select **New Form** to begin creating your form.

1. Enter a name for your form, you can also enter a description if needed.

1. Click **Add New** to add a new question to the form. 

   ![](Images/img66.png)

1. Choose from Choice, Text, Rating, or Date questions. You can also click More question types Drop down list for more question types in Microsoft Forms to select Ranking, Likert, File upload, or Net Promoter Score® questions. 

   ![](Images/img67.png)

1. For now select **Choice**. Enter the text you want to display for the question and each of the choices. Click **Add Option** to add more choices than the default two choices.

1. Click **Add New** to add more questions to your form. Now select **Text**.

1. For text questions, select the **Long Answer** option if you want a larger text box displayed on the form.

1. Text questions also allow you to set restrictions when you need to have numbers as the answer. For this click on **More options** button, and then select **Restrictions**.
    
   ![](Images/img68.png)
   
   ![](Images/img69.png)
  
1. Now from the drop-down select **Between** and enter the number. You can choose to restrict the numbers by selecting from the various options such as Greater than, Less than, Between, and many others.
   
   ![](Images/img70.png)

1. Click Preview at the top of the design window to see how your form will look on a computer. Now to test your form, enter answers for the questions in preview mode and then click on **Submit**.

   ![](Images/img71.png)
   
   ![](Images/img72.png)

1. Now click on **Back** and select the **Responses tab**. From here you can see summary information data about your form, such as the number of responses and the average time it took for respondents to complete your form.

   ![](Images/img73.png)

### Task 2 : Change a form theme and Sharing forms

In this task, you will learn how to customize the theme of your newly created form and the means to share it.

1. Click on the **Theme** at the top right of the design window and pick the color or background you want.

   ![](Images/img74.png)

1. If you prefer to customize the theme, within the theme page scroll down and select **+ Customize theme** button. From here you can either upload an image by clicking on **Upload image** icon or customize the color of your choice by clicking on **Customize color** button.

   ![](Images/img75.png)

1. From the top navigation menu click on **Share**. From here based on your requirement you can either use a link, QR code, Embed, or Email option to share your form.

   ![](Images/img76.png)
   
1. To know more about forms refer to https://support.microsoft.com/en-us/forms.

# Exercise 5 : Setup Basic PowerBI Report from a sample Excel 

In this exercise, you will learn how to create a Power BI report from sample data and visualize it.

### Task 1: Import data to PowerBI

In this task, you will import sample financial data to PowerBI. 

1. Open a new browser window and log in to the office365 center at https://www.office.com.

1. When prompted enter the username and password of the user which you have created in the the Exercise 1 task 1. For example Odl_User-DeploymentId. 

1. In office365 portal from the **App launcher** click on **All apps** and in the search bar search for **Power BI**, from **Open context menu** click on **Open in new tab**, this will redirect you to the **Power BI** web page.

1. Download sample data from https://docs.microsoft.com/en-us/power-bi/create-reports/sample-financial-download

   ![](Images/img77.png)
   
1. In Power BI, from the left navigation menu select **My workspace**, click on **New**, and from the drop-down select **Upload a file**.

   ![](Images/img78.png)

1. Select **Local File**, browse to where you saved the Financial Sample data file, and click on **Open**.

   ![](Images/img79.png)

1. On the **Local File page**, select **Import**.


### Task 2 : Visualize data

In this task, you will visualize the data which you had imported in the previous task by using various visualization options available in PowerBI.

1. Click on **Financial Sample** dataset. From the dropdown of **+Create a report**, click on **From scratch**.

   ![](Images/image11.png)
   
   ![](Images/image12.png)

1. The report opens in the Editing view and displays the blank report canvas. On the right are the **Visualizations**, **Filters**, and **Fields** panes.

   ![](Images/img81.png)

1. Now let us create visualizations. Let's say your manager wants to see profit over time. To do this, in the Fields pane select **Profit**. Power BI displays a column chart with one column.

   ![](Images/img82.png)

1. From Fields pane, select **Date**. Power BI updates the column chart to show profit by date. 

   ![](Images/img83.png)

1. We can also create a map visualization. In this, we will check which countries are the most profitable.

1. Select a blank area on your report canvas, from the **Fields** pane, select **Country**, and **Profit** field. Power BI creates a map visual with bubbles representing the relative profit of each location.

   ![](Images/img84.png)

1. In this way you can explore through other visualization options.

1. To save your report from the top navigation menu, select **File** and click on **Save**, provide a name for your report, and select **Save**.

   ![](Images/img85.png)

1. To learn more about **Power BI** refer to https://docs.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview.

# Exercise 6 : Explore MyAnalytics

Microsoft MyAnalytics, formerly Delve Analytics, is an application designed to help employees and their managers gain insight into how workers spend their time, intending to optimize tasks and make them more efficient. With this application, you can track data such as time spent in meetings, Outlook emails, productivity, and time spent working late.

*New users won’t have enough data to view various analytical breakdowns within the application. You will see a message stating that “MyAnalytics works best with at least 4 weeks of data. Please check back later for your insights”. Your screen would look like this*: 

   ![](Images/M3E6T1Step301.png) 

   **Note**: Once you have enough data, you can view various insights in MyAnalytics, or Else can try with your personal account with atleast office 365 license. Let us now explore these features. 
 
In this exercise, you will explore MyAnalytics application.

   **Note**: The Data may not appear in **MyAnalytics** of your lab environment as there are no activity performed yet.

1. Open a new browser window and log in to the office365 center at https://www.office.com.

1. When prompted enter the username and password of the user which you have created in the the Exercise 1 task 1. For example Odl_User-DeploymentId. 

1. In the office365 portal from the **App launcher** click on **All apps** and in the search bar search for **MyAnalytics**, from **Open context menu** click on **Open in new tab**, this will redirect you to the **MyAnalytics** web page.

1. Under **Apps**, select **MyAnalytics** and from **Open context menu** click on **Open in new tab**. This will redirect you to the Microsoft **MyAnalytics** web page.

1. From the left navigation menu select **Home**. This displays statistics about your work patterns over the past month, including your focus and collaboration time, how many days you were able to disconnect from work, and how effectively you are networking with your coworkers.

   ![](Images/img206.png)

1. From the left navigation menu select **Focus**. The Focus page shows weekly averages for the time you have available to focus and time spent collaborating with others in your network.
   
   ![](Images/img207.png)

1. Select **Wellbeing** this page shows how well you are disconnecting from work during your time off and suggests ways to reduce stress and burnout.
   
   ![](Images/img208.png)

1. Select **Network** this page shows how many people you actively connect with in the last month and gives you suggestions on how to improve connections with your most important contacts, such as your manager or your direct reports.

   ![](Images/img209.png)

1. Select **Collaboration** this helps you reflect on how effectively you spend your time in meetings, email, chats, and calls.

   - **Weekly average** : The Weekly average section shows an estimate of how much time you spent in meetings, email, chats, and calls in the past four weeks. 
   
   - **Meeting habits** : The Meeting habits view shows data about your meeting habits based on the meetings on your calendar over the past four weeks. It helps you understand the number of times each of these meeting types occurs out of the total number of meetings you organized or accepted to attend.
   
   - **Communication habits** : The Communication habits section shows the total number of chats (instant messages) and emails sent and read during each hour of the day in the past four weeks.
   
   ![](Images/img210.png)

1. To learn more about **MyAnalytics** refer to https://docs.microsoft.com/en-us/workplace-analytics/myanalytics/mya-landing-page.


# Exercise 7 : Explore Microsoft EndPoint Manager 

Microsoft Endpoint Manager helps deliver the modern workplace and modern management to keep your data secure, in the cloud and on-premises. Endpoint Manager includes the services and tools you use to manage and monitor mobile devices, desktop computers, virtual machines, embedded devices, and servers. Endpoint Manager combines services like Microsoft Intune, Configuration Manager, Desktop Analytics, co-management, and Windows Autopilot.

In this exercise, you will explore various available options in Microsoft EndPoint Manager.

Before we explore the Microsoft EndPoint Manager, we need to activate the **Enterprise Mobility + Security e5** license in order to view the **Endpoint Manager**.

1. Open a new browser window and log in to the admin center at https://admin.microsoft.com.

1. When prompted, use the credentials provided in the Environment Details page to log in to the admin center.

1. From the navigation menu scroll down to Admin centers and select Azure Active Directory, the Azure Active Directory overview page will appear.

   ![](Images/img116.png)

1. On the left side of the page scroll down to the **Security**.

   ![](Images/img127.png)

1. In the **Security** page select **Conditional access**.

   ![](Images/img128.png)
   
1. If you see **Create your own policies and target specific conditions like Cloud apps, Sign-in risk, and Device Platforms with Azure AD Premium.**, then select it. else ignore **7&8**.

   ![](Images/p5license.png)
   
1. Select the **Enterprise Mobility + Security e5** license and click on the **Free Trial** and select **Activate**. 

   ![](Images/p5activate.png)

1. Refresh your browser window once you see a notification that you have **Successfully activated Enterprise Mobility + Security e5**

   ![](Images/p5activated.png)

1. Switch back to **Admin Center** portal. Refresh your browser window. Now from the navigation menu scroll down to Admin centers, and select **Endpoint Manager**. This will redirect you to the Endpoint Manager admin center.

   ![](Images/img196.png)

1. From the navigation pane, select **Dashboard** to display overall details about the devices and client apps in your Intune tenant.

   ![](Images/img197.png)

1. Microsoft Intune is a cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM). Intune is part of Microsoft's Enterprise Mobility + Security (EMS) suite.

1. From the navigation pane, select **Devices**  to display details about the enrolled devices in your Intune tenant.

1. The Devices, **Overview** pane has several tabs that allow you to view a summary of the following statuses and alerts:

      -  **Enrollment status** - Review details about Intune enrolled devices by platform and enrollment failures.
      
      -  **Enrollment alerts** - Find more details about unassigned devices by platform.

      -  **Compliance status** - Review compliance status based on device, policy, setting, threats, and protection. Additionally, this pane provides a list of devices without a compliance policy.

      - **Configuration status** - Review configuration status of device profiles, as well as profile deployment.
      
      - **Software update status** - See a visual of the deployment status for all devices and all users.
      
        ![](Images/img198.png)

1. From the Devices **Overview** pane, select **Compliance policies**  to display details about compliance policies for devices managed by Intune. Compliance requirements are essentially rules, such as requiring a device PIN or requiring device encryption. Device compliance policies define the rules and settings that a device must follow to be considered compliant.

   ![](Images/img199.png)

1. From the Devices Overview pane, select **Conditional Access**, and select **New Policy** to create policy. Conditional Access refers to ways you can control the devices and apps that are allowed to connect to your email and company resources.

   ![](Images/img200.png)

1. From the navigation pane, select Devices and select **Configuration profiles** to display details about device profiles in Intune(**Reference**). 

   ![](Images/img201.png)

1. From here you can configure device restriction settings like Allow or block the device camera, control access to Google Play, app stores, viewing documents, and gaming, and much more.

1. In the  **Devices** page select **All devices** to display details about your Intune tenant's enrolled devices. This list of devices show key details about compliance, OS version, and last check-in date. 

   ![](Images/img202.png)
  
1. From the navigation pane select **Apps**. On the apps page select **All apps** this displays a list of apps that have been added to Intune. You can add a variety of different app types based on the platform to Intune. Once an app has been added, you can assign it to groups of users.

   ![](Images/img203.png)

1. From the navigation pane, select **Users** to display details about the users that you have included in Intune.

   ![](Images/img204.png)

1. From the navigation pane, select **Groups** to display details about the Azure Active Directory (Azure AD) groups included in Intune. As an Intune admin, you use groups to manage devices and users.

   ![](Images/img205.png)
   
1. To learn more about Endpoint Manager refer to https://docs.microsoft.com/en-us/mem/intune/fundamentals.

## Conclusion

With the help of this module, you learned how to create M365 groups, forms, plans and assign tasks using Planner, also visualized sample data using Power BI and explored through EndPoint Manager
