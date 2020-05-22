---
title: Configure Logging and Tracing
description: Configure Logging and Tracing
author: dansimp
ms.assetid: 4f89552f-e949-48b0-9325-23746034eaa4
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 06/16/2016
---


# Configure Logging and Tracing


You can centrally configure optional logging and tracing using Administrative templates. This may be helpful when diagnosing any problems related to Advanced Group Policy Management (AGPM).

A user account with the AGPM Administrator (Full Control) role, the user account of the Approver who created the Group Policy Object (GPO) used in these procedures, or a user account with the necessary permissions in AGPM is required to complete these procedures. Additionally, a user account with access to the AGPM Server is required to initiate logging on the AGPM Server. Review the details in "Additional considerations" in this topic.

**To configure logging and tracing for AGPM**

1.  In the **Group Policy Management Console** tree, edit a GPO that is applied to all Group Policy administrators for which you want to turn on logging and tracing. (For more information, see [Editing a GPO](editing-a-gpo-agpm30ops.md).)

2.  In the **Group Policy Management Editor** window, click **Computer Configuration**, **Policies**, **Administrative Templates**, **Windows Components**, and **AGPM**.

3.  In the details pane, double-click **AGPM: Configure logging**.

4.  In the **Properties** window, click **Enabled**, and configure the level of detail to record in the logs.
