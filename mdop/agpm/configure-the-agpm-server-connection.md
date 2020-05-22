---
title: Configure the AGPM Server Connection
description: Configure the AGPM Server Connection
author: dansimp
ms.assetid: 9a42b5bc-41be-44ef-a6e2-6f56e2cf1996
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 06/16/2016
---


# Configure the AGPM Server Connection


Advanced Group Policy Management (AGPM) stores all versions of each controlled Group Policy object (GPO) in a central archive, so Group Policy administrators can view and modify GPOs offline without immediately impacting the deployed version of each GPO.

A user account with the AGPM Administrator (Full Control) role, the user account of the Approver who created the GPO used in these procedures, or a user account with the necessary permissions in Advanced Group Policy Management is required to complete these procedures for centrally configuring archive locations for all Group Policy administrators. Review the details in "Additional considerations" in this topic.

## Configuring the AGPM Server connection


As an AGPM Administrator (Full Control), you can ensure that all Group Policy administrators connect to the same AGPM Server by centrally configuring the setting. If your environment requires separate AGPM Servers for some or all domains, configure those additional AGPM Servers as exceptions to the default. If you do not centrally configure AGPM Server connections, each Group Policy administrator must manually configure the AGPM Server to be displayed for each domain.

-   [Configure an AGPM Server for all Group Policy administrators](#bkmk-defaultarchiveloc)

-   [Configure additional AGPM Servers for all Group Policy administrators](#bkmk-additionalarchiveloc)

-   [Manually configure an AGPM Server for your account](#bkmk-manuallyconfigurearchiveloc)