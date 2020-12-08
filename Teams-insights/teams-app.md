---
ROBOTS: NOINDEX,NOFOLLOW
title: Teams insights app
description: Teams insights app -- description, installation, using it, and FAQ
author: paul9955
ms.author: v-pausch
ms.topic: article
localization_priority: normal 
ms.prod: Mya

---

# Teams insights app

The Teams Insights app helps you stay on top of your tasks and get more done by providing insights for improving your collaboration, wellbeing, and productivity. It derives these insights by summarizing your Office 365 data – data that you already have access to – about emails, meetings, calls, and chats. 

By using Insights, you and your teams can: 

 * **Stay connected** – Teams Insights will help you stay on top of your collaboration with colleagues through features such as AI-based task suggestions and meeting assistance. 
 * **Protect time** – Teams Insights will help you find more time to eliminate distractions, stop multi-tasking, and focus on your core priorities. 

The insights that this app presents are completely personal and private. Only you – not your manager and not the system administrator – can see your insights. For more information, see the following section, [Privacy guide](#privacy-guide). 

## Privacy guide 

When data is processed in the Teams Insights app, Microsoft protects employee privacy and fully complies with local regulations, such as the General Data Protection Regulation (GDPR). Insights protects privacy in the following ways: 

 * **Personal and private** – Content in your Insights are personal and private and are only available to you and cannot be accessed by anybody else in your organization, including your IT admin or your manager. 

 * **Everyone's data is kept private** – Teams Insights does not include any new personally identifiable information about anybody else in your organization. The insights and actions are based on information generated by you and your organization just by going about your regular workday. Your insights are based on information that you already have access to but can’t quickly aggregate without help. 

 * **Mailbox security** – Teams Insights uses Exchange Online email and calendar data and processes and stores any insights or actions inside your Exchange Online mailbox, so data security is built in and enforced by Exchange. 

 * **GDPR compliant** – Microsoft complies with the GDPR when providing insights and actions in the app. 

### How it works 

The insights and actions in the Insights app are based on your Exchange Online mailbox data, such as email and calendar data. The insights are derived from data that is already available to you in your Exchange Online mailbox. For example, if you want to determine what commitments you made to others, you could manually review each email in your mailbox. The Insights app simply saves you from this tedious process. 

> [!Note] 
> To have access to the full functionality of the Insights app, you need a [MyAnalytics](https://myanalytics.microsoft.com/) license.

### GDPR compliance 

Microsoft helps data controllers meet the following obligations for the Insights app: 
* **Secure and protect users’ personal data** &ndash; All data is stored in the employees’ Exchange Online mailbox. The computed metrics, such as tasks, are appended to the mailbox. Thus, the Insights meets this obligation by virtue of Exchange Online also meeting the obligation: 
   * Microsoft will not mine customer data in Exchange Online for advertising. 
   * Microsoft will not voluntarily disclose Exchange Online customer data to law enforcement agencies. 
   * Microsoft will meet all requirements related to encryption of Exchange Online data and implement controls to reduce security risks and help ensure business continuity, as described in ISO 27001 and 27018. 
* **Notify users in the event that a breach is detected** &ndash; Microsoft will notify customer privacy contacts within 72 hours of Microsoft becoming aware of a breach by using Office 365 incident response standard operating procedures. 
* **Honor user requests (DSRs) to export, delete, or restrict processing personal data** &ndash; Microsoft supports your need to honor user requests in the following ways. 
   * **Data export requests** &ndash; Users can view the insights in the Briefing email and manage it if they want to have permanent copies of their information. 
   * **Request to restrict processing** &ndash; Use PowerShell to opt employees out of the Briefing email. Or employees can individually unsubscribe from the Briefing email to restrict processing of their data. 
   * **Delete employee data** &ndash; Sign in to [Azure Active Directory admin center](https://aad.portal.azure.com/) and then remove the employee's data through the User Management Portal. 

To learn more, see [GDPR compliance](https://www.microsoft.com/trustCenter/privacy/gdpr). 

## Install Insights 

This section describes how to install the Insights Teams app for yourself. (If you are an admin who is tasked with installing the Insights Teams app for an organization, see [Admin tasks: Quick-start guide](#admin-tasks-quick-start-guide).)  

1. Open Microsoft Teams on the web or in a desktop client. 

2. At the bottom of the Microsoft Teams app bar (on the left), select **Apps**: 

   ![Apps icon in Teams](Images/teams-apps.png)
 
3. In the search field under **Apps**, type **Insights**:
   
   ![Search for Insights](Images/apps-search-insights.png)

4. Select the **Insights** app:

   ![Select Insights app](Images/insights-app-teams.png)

5. Select **Add for me**:

   ![Add for me button](Images/add-for-me-new-410.png)

This adds the app to all the places where you might use Microsoft Teams, including the Teams desktop client, Teams on the web, and Teams on a mobile device.   

> [!Note] 
> You can also locate the Insights app through this link: https://aka.ms/InsightsTeamsApp. 

### Pin the app 

After you pin a Teams app, it appears on the Teams app bar (the left navigation bar). 

#### On desktop and web client 

1. Select **More** (the ellipsis) on the Microsoft Teams app bar.  

2. Right-click any app icon and select **Pin** to make and keep your app visible in the Teams app bar. 
   
   ![Pin an app in Teams](Images/pin-an-app-75.png)

> [!Tip] 
> You can reorder apps in the Teams app bar by dragging and dropping icons. For more information about pinning and unpinning apps in Microsoft Teams, see [Pin an app for easy access](https://support.microsoft.com/en-us/office/pin-an-app-for-easy-access-3045fd44-6604-4ba7-8ecc-1c0d525e89ec). 
 
#### On the iOS and Android mobile platforms

1. Select **More** (the ellipsis) on the Microsoft Teams app bar.  

2. Select **Reorder** and drag and drop the app so it is no longer in the More section. 

3. Select **Done** to save your changes. 

## Use the Insights app 

The Teams insights app comes with a range of features that you can find by selecting one of the following tabs:

* [Stay connected](#stay-connected) 
* [Protect time](#protect-time-tab) 

> [!Note] 
> As you use the Teams insights app, you can provide feedback about the app to Microsoft. To learn how, see [How can I send feedback to Microsoft about the Insights app?](#q4-how-can-i-send-feedback-to-microsoft-about-the-insights-app).


### Stay connected  

Insights in the **Stay connected** tab help you stay connected with your collaborators and improve your productivity. 
   
   ![Stay connected](/WorkplaceAnalytics/images/mya/use/)

The **Stay connected** tab can contain insights such as the following: 

* [Identify and pin important collaborators](#identify-and-pin-important-collaborators)  
* [Set up 1:1 meeting reminders](#set-up-11-meeting-reminders) 
* [1:1 meeting suggestions](#11-meeting-suggestions) 
* [Reschedule a 1:1 in case of conflict](#reschedule-a-11-in-case-of-conflict) 
* [Stay on top of outstanding task suggestions](#stay-on-top-of-outstanding-task-suggestions) 
* [Catch up on unread documents shared with you](#catch-up-on-unread-documents-shared-with-you) 
* [@Mentions for pinned important contacts](#-for-pinned-important-contacts) 
* [Upcoming meetings that need your RSVP](#upcoming-meetings-that-need-your-rsvp) 
 
#### Identify and pin important collaborators  

You might receive insights from various people but some items might deserve more attention than others. For example, an outstanding task suggestion from your manager or a message from a key customer would likely be of higher priority.  

Based on your collaboration patterns, you can pin some of your contacts as important. All insights from pinned important contacts are shown with higher priority at the top of the page.  

To pin a contact, select the **pin** icon on the bottom left below the contact’s name: 
   
   ![Pin a contact](Images/pin-contact.png)

To unpin a contact, select the **unpin** icon: 
   
   ![Unpin a contact](Images/unpin-contact.png)

#### Set up 1:1 meeting reminders 

While staying in touch with top collaborators can be difficult, a quick 1:1 meeting with key contacts can help you nurture your professional network. Teams insights can help you set a target 1:1 meeting frequency for each contact and provide  you with meeting recommendations if you are falling out of touch.  

In the following example, if Lynne was an important colleague, you could set up a monthly 1:1 meeting target with Lynne by selecting the **people** icon and then selecting the **Monthly** reminder frequency. Insights will keep track of your meetings with Lynne and if you have not had a 1:1 with Lynne for a month, it will suggest setting up a 1:1 meeting and help you schedule it. 

If you want to remove the 1:1 meeting target, you can select the **people** icon and select **None**. If you are a manager, Insights will automatically suggest a biweekly 1:1 meeting with your direct report.  
   
   ![MyAnalytics settings](Images/1-1-meeting-target-75-80.png)

#### 1:1 meeting suggestions 

If you’ve set up a target 1:1 meeting cadence with your colleague through the Insights app and are falling out of the set cadence, Insights will remind you to set up a 1:1 meeting and help you schedule it.  

In the following example, you can select one of the proposed meeting times and then select **Send invite** to send a meeting invitation to Lynne. Insights will only show meeting time blocks when both of you are available to meet. If none of the suggested time blocks work, you can select **View calendar for other items** to open the Teams calendar and schedule a meeting on your own. 
   
   ![Schedule a 1:1](Images/schedule-1-1.png)

#### Reschedule a 1:1 in case of conflict  

Insights also helps you follow through on your intent to have 1:1 meeting with your colleagues. If, for some reason, the 1:1 meeting invitation you sent to your colleague has a conflict, Insights will help you quickly reschedule the meeting. 

In the following example, if your meeting with Lynne has a conflict, Insights will remind you of the conflict ahead of time and you can quickly choose a new time for the 1:1 meeting and select **Reschedule** to move the meeting invitation. 
   
   ![1:1 has a conflict](Images/1-1-conflict.png)

#### Stay on top of outstanding task suggestions 

It is easy to lose track of commitments that you've made to your colleagues in email. This insight helps you make sure that nothing falls through the cracks by reminding you of tasks that you've agreed to do. It is based on emails that you've sent and requests from your colleagues during the last 14 days of email communication, and includes: 

* **Commitments** &ndash; Something that you promised or committed to do for someone else in an email 
* **Requests** &ndash; Something that another person asked you to do in an email 
* **Follow-ups** &ndash; Something that you asked for from someone else in an email 

In the following example, you can select **Re: Sync up on Regression Tests** to open the email in which you can follow up or select **Done** to confirm that you’ve already followed up.  
   
   ![Sync on regression tests email](Images/sync-up.png)

#### Catch up on unread documents shared with you 

Have you searched for that document that you planned to read but you just cannot find it? With so many documents shared across meetings and emails, it can be difficult to stay caught up on documents shared by your colleagues. With this insight you can see a list of the shared OneDrive and SharePoint documents that you need to catch up on.  

In the following example, to open the document, select **Open**. To open the email through which the document was shared, select **Re: Sync on Regression Test**. 
   
   ![Unread document from the meeting](Images/unread-doc.png)

#### @Mentions for pinned important contacts 

@Mention is a common way to tag colleagues on important work items. Insights can help you quickly triage recent @Mentions from pinned contacts so that you are caught up on important conversations and tasks in Teams. In the following example, select **Go to comment** to open the conversation and follow up. 
   
   ![Sync on virtual commute research](Images/sync-virtual.png)

#### Upcoming meetings that need your RSVP 

Let your colleagues know if you can join their meeting so that they can run effective meetings. Meeting attendance information helps meeting organizers better plan and prepare for meetings, and reschedule if needed.  

In the following example, select **Sync on Proposal** to open the meeting invitation for more context on the meeting and then select **Accept** to accept (or **Decline** to decline) the meeting invitation. 
   
   ![You haven't RSVP'd](Images/havent-rsvpd.png)

### Protect time tab 

Research shows that on average it takes 23 minutes to refocus on a task after a distraction, and constant distraction during focused work can cause higher stress, lower productivity, and bad mood. Further, it can be hard to go deep on challenging work if you have only small chunks of time to focus between meetings or are easily distracted by incoming emails and chats. Blocking a few hours every day to focus without interruptions can help you make progress on your important tasks and projects. 

Insights can help you protect time for focused work and minimize notifications (and thus distraction) by Teams and Skype for business chats and calls during your focus time. 

In the following example, select **Book Time** to reserve the time slot for focused work. If you don’t need the time anymore, you can select **Remove slot** to free up your calendar. You can also select edit (the pencil icon) to change the name of the focus time block; this automatically updates the subject of this focus-time booking on your calendar. 
   
![Book focus time](Images/book-time-2.png)  

## Frequently asked questions 

##### Q1. Does the Teams insights app comply with GDPR? 

**A1.** Yes. The Teams Insights app complies with GDPR requirements. 

##### Q2. Can users see information about other users in the Insights app? 

**A2.** The Insights app only includes existing information that’s already available in the user’s mailbox. It summarizes documents, emails, and meetings to make it easier for the user to find what’s most important for their day ahead. Users cannot see any new information about other users that wasn’t already available in their mailboxes. 

##### Q3. Can my manager, administrator, or anyone else at my organization see what’s in my Insights app? 

**A3.** No, the content in the Insights app is private and visible to you and only you. All information in the Insights app is from your mailbox and stored in your mailbox. Everything you see in the Insights app is information that you already have access to in your mailbox. Insights just makes it easier to find items that might need attention. 

##### Q4. How can I send feedback to Microsoft about the Insights app? 

**A4.** There are two ways to provide feedback through the Insights app: 

* At the bottom of every Insight is the question, "Is this helpful?" Select **Yes** or **No** to provide feedback.  
   
   ![Is this helpful? Yes No](Images/is-helpful.png)

* Every page in the Insights app has the question, "Is this helpful?" at the bottom right corner. Select **Yes** or **No** to provide feedback.  
   
   After you have selected **Yes** or **No** on one of these options, a dialog box appears in which you can share more. Select the **Allow Microsoft to contact …** box if you’d like Microsoft to contact you to follow up on your feedback. 
   
   ![Thanks for the feedback](Images/thanks-for-feedback-70-80.png)
   
##### Q5. What data does the Teams Insights app use? 

**A5.** Insights uses: 

* Information from email items: 
  * Metadata. This includes the email's timestamp, names of sender and recipients, and "read" status. 
  * Task statements. Statements that people have made in the body text of the email. These statements are used to create [task cards](/WorkplaceAnalytics/MyAnalytics/use/mya-outlook-add-in/mya-add-in-to-do.md) for your use only.  
* Information from calendar items: 
  * Type (meeting or appointment) 
  * Status (busy, free, out-of-office, tentative) 
  * Category 
  * Subject 
  * Duration 
  * Attendees 
* OneDrive SharePoint data: Insights shows a count of OneDrive and SharePoint documents that you have worked on. 

Insights does not use:  

 * Email and calendar data from people outside your organization, with the following exception: Insights uses data that is present in your own Office 365 mailbox. For example, if you conduct a meeting with a person outside your organization, the start and end times of that meeting can be found in your mailbox and are visible to you. This data, therefore, can be used in computations about your collaboration history. 

##### Q6. Why do I not see the insights and suggestions that are described in the documentation?

**A6.** To get access to the full functionality of the Insights app, check with your administrator to verify that you have MyAnalytics enabled. 

## Admin tasks: Quick-start guide

[Teams Service Administrators](https://docs.microsoft.com/microsoftteams/using-admin-roles#teams-roles-and-capabilities) can choose to deploy and pin the app for all users or particular departments [through custom policies](https://docs.microsoft.com/microsoftteams/teams-app-setup-policies). 

Complete the steps in the following four mini-playbooks to get the Teams Insights app up and running for people in your organization. 

1. Turn on the Teams Insights app for your organization: 
[Release the Insights app within your organization](/WorkplaceAnalytics/MyAnalytics/Use/Release-the-Insights-app.pdf). 

   > [!Note] 
   > To allow or block specific users in your organization from using Insights, do the following: 
   > 
   > 1. Make sure that Insights is turned on for your organization on the [Manage apps](https://docs.microsoft.com/microsoftteams/manage-apps) page. 
   > 
   > 2. Create a custom-app permission policy and assign it to those users. To learn more, see [Manage app permission](https://docs.microsoft.com/microsoftteams/manage-apps) policies in Teams. 

2. Install the Teams Insights app for all employees in your organization: [Install the Insights app](/WorkplaceAnalytics/MyAnalytics/use/Install-the-Insights-app.pdf). 

3. Pin the Teams Insights app to the left navigation pane of Teams for all employees in your organization: [Pin the Teams Insights app](/WorkplaceAnalytics/MyAnalytics/use/Pin-the-Insights-app.pdf). 

4. Now that the Teams Insights app is available for employees, they can follow these steps to locate and open it: [Find and open the Insights app](/WorkplaceAnalytics/MyAnalytics/use/Find-and-open-the-Insights-app.pdf). 
 