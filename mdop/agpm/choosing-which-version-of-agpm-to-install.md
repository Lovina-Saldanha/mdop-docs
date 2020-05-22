---
title: Choosing Which Version of AGPM to Install
description: Choosing Which Version of AGPM to Install
author: dansimp
ms.assetid: 31357d2a-bc23-4e15-93f4-0beda8ab7a7b
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 04/05/2017
---


# Choosing Which Version of AGPM to Install


Each release of Microsoft Advanced Group Policy Management (AGPM) supports specific versions of the Windows operating system. We strongly recommend that you run the AGPM Client and AGPM Server on the same line of operating systems. For example, Windows 10 with Windows Server 2016, Windows 8.1 with Windows Server 2012 R2, and so on.

We recommend that you install the AGPM Server on the most recent version of the operating system in the domain. AGPM uses the Group Policy Management Console (GPMC) to back up and restore Group Policy Objects (GPOs). Because newer versions of the GPMC provide additional policy settings that are not available in earlier versions, you can manage more policy settings by using the most recent version of the operating system.

All versions of AGPM can manage only the policy settings that were introduced in the same version or an earlier version of the operating system on which AGPM is running. For example, if you install AGPM 4.0 SP2 on Windows Server 2012, you can manage policy settings that were introduced in Windows Server 2012 or earlier, but you cannot manage policy settings that were introduced later, in Windows 8.1 or Windows Server 2012 R2.

If the version of the GPMC on your AGPM Server is older than the version on the computers that administrators use to manage Group Policy, the AGPM Server will be unable to store any policy settings that are not available in the older version of the GPMC. For a spreadsheet of Group Policy settings included in Windows, see [Group Policy Settings Reference for Windows and Windows Server](https://go.microsoft.com/fwlink/p/?LinkId=613627).

## AGPM 4.0 SP3


If you are using computers that are running Windows 10 to manage GPOs, you must use AGPM 4.0 SP3. You cannot install earlier versions of AGPM on computers that are running the Windows 10 operating system.
