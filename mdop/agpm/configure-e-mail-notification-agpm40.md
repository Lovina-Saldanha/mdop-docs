---
title: Configure E-Mail Notification
description: Configure E-Mail Notification
author: dansimp
ms.assetid: 06f19556-f296-4a80-86a4-4f446c992204
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 06/16/2016
---


# Configure E-Mail Notification


When an Editor or a Reviewer attempts to create, deploy, or delete a Group Policy Object (GPO), a request for this action is sent to a designated e-mail address or addresses so that an Approver can evaluate the request and implement or deny it. You determine the e-mail address or addresses to which notifications are sent, as well as the alias from which notifications are sent.

A user account with the AGPM Administrator (Full Control) role or necessary permissions in Advanced Group Policy Management (AGPM) is required to complete this procedure. Review the details in "Additional considerations" in this topic.

**To configure e-mail notification for AGPM**

1.  In the **Group Policy Management Console** tree, click **Change Control** in the forest and domain in which you want to manage GPOs.

2.  In the details pane, click the **Domain Delegation** tab.

3.  In the **From e-mail address** field, type the e-mail alias for AGPM from which notifications should be sent.

4.  In the **To e-mail address** field, type a comma-delimited list of e-mail addresses of Approvers who should receive requests for approval.

5.  In the **SMTP server** field, type a valid SMTP mail server.