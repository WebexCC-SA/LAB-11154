# Chapter 3 – Webex Calling Features

## Summary

In this lab, you will use Webex Calling features in Control Hub to provision a government agency/site. We often see these features requested when we setup trials for Federal, State, Local, and with businesses that work on Government contracts. The telephony features used in government agencies include a range of traditional and advanced capabilities that support secure, efficient communication and streamline operations in government environments.<br><br><br>Webex Calling Features:

- Auto Attendants: Automated system to answer and route calls 24/7.

- Hunt Groups: Directs calls to employees in a set order or pattern.

- Call Queues (Native all Queues &amp; Customer Assist): Manages incoming calls with queueing and routing.

- Paging Groups: Sends announcements to multiple users at once.

- Shared and Monitored Lines: One number on multiple phones; monitor line status and activity.

- Call Recording: Record desk phone/Webex App calls; options for always, on-demand, pause/resume.

- End User Portal: (user-usgov.webex.com) Manage personal calling settings like forwarding and voicemail.

- Hot Desking: Staff using shared workspaces can sign in and book a shared phone for their workday.

- Push to Talk / Intercom: allow users to treat their physical devices or soft clients as a one-way or two-way intercom.

- 9800 Series Phone Action Button - trigger alerts or emergency situations

We are doing all of this set up manually but know there are trial/production options available to use bulk tools and or APIs for much of this configuration work. 3rd party integrations with AD or SSO are very much possible and in most cases easy to do, but again not in scope in this Lab.

Reference Dial Plan that you will setup (your users are already configured).

| User / workspace | Extension | Feature | Extension |
| --- | --- | --- | --- |
| Admin | 1000 | Voicemail Portal | 8888 |
| User1 | 1001 | Auto Attendant | 2000 |
| User2 | 1002 | Hunt Group | 3000 |
| DeskPhone | 1100 | Call Queue | 4000 |
| DeskPro | 1101 | Customer Assist Queue | 4500 |
| | | Virtual Extension | 5000 |
| | | Paging | 7243 |

## Requirements

We will be leveraging the existing set up you did in Chapters 1 &amp; 2. We will be testing on your PC using the Webex application, your mobile device (native dialer and Webex application), configured desk phone, and DeskPro. We also need to leverage your pc to interface with Control Hub via your browser for user/feature set up and editing.
