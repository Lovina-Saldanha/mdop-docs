---
title: Create a New Controlled GPO
description: Create a New Controlled GPO
author: dansimp
ms.assetid: f89eaae8-7858-4222-ba3f-a93a9d7ea5a3
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 06/16/2016
---


# Create a New Controlled GPO


New Group Policy Objects (GPOs) created through the **Change Control** folder will automatically be controlled, enabling you to manage them.

A user account with the Approver or AGPM Administrator (Full Control) role or necessary permissions in Advanced Group Policy Management (AGPM) is required to complete this procedure. Review the details in "Additional considerations" in this topic.

**To create a new GPO with change control managed through AGPM**

1.  In the **Group Policy Management Console** tree, click **Change Control** in the forest and domain in which you want to manage GPOs.

2.  Right-click **Change Control**, and then click **New Controlled GPO**.

3.  In the **New Controlled GPO** dialog box:

    1.  Type a name for the new GPO.

    2.  Optional: Type a comment for the new GPO to be displayed in the **History** for the GPO.
