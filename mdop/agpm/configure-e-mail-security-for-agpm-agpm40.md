---
title: Configure E-Mail Security for AGPM
description: Configure E-Mail Security for AGPM
author: dansimp
ms.assetid: b9c48894-0a10-4d03-8027-50ed3b02485a
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 06/16/2016
---


# Configure E-Mail Security for AGPM


By default, e-mail notifications sent because of actions in Advanced Group Policy Management (AGPM) are not encrypted and are sent through SMTP port 25. However, you can configure e-mail security for AGPM by using registry settings to specify whether to use Secure Sockets Layer (SSL) encryption and which SMTP port to use.

By encrypting AGPM e-mail notifications, you can better protect those that could reveal sensitive information about your organization’s security. Encrypting e-mail notifications is recommended when they are being relayed through remote mail servers, and may be required by some compliance regulations.

**Caution**  
Incorrectly editing the registry may severely damage your system. Before making changes to the registry, you should back up any valued data on the computer.

 

A user account that has the AGPM Administrator (Full Control) role, the user account of the Approver who created the Group Policy Object (GPO) used in these procedures, or a user account that has the necessary permissions in AGPM is required to complete these procedures. Review the details in "Additional considerations" in this topic.

**To configure e-mail security for AGPM by using Group Policy preferences**

1.  In the **Group Policy Management Console** tree, edit a GPO that is applied to all AGPM Servers for which you want to configure e-mail security. (For more information, see [Editing a GPO](editing-a-gpo-agpm40.md).)