---
title: Configure AGPM Server Connections
description: Configure AGPM Server Connections
author: dansimp
ms.assetid: 6062b77b-2fd7-442c-ad1b-6f14419ebd5f
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop
ms.mktglfcycl: manage
ms.sitesec: library
ms.prod: w10
ms.date: 06/16/2016
---


# Configure AGPM Server Connections


All versions of each controlled Group Policy Object (GPO) are stored in a central archive so that Group Policy administrators can view and modify GPOs offline without immediately impacting the deployed version of each GPO.

A user account with the AGPM Administrator (Full Control) role, the user account of the Approver who created the GPO used in these procedures, or a user account with the necessary permissions in Advanced Group Policy Management (AGPM) is required to complete these procedures for centrally configuring archive locations for all Group Policy administrators. Review the details in "Additional considerations" in this topic.

## Configuring AGPM Server connections


As an AGPM Administrator, you can ensure that all Group Policy administrators connect to the same AGPM Server by centrally configuring the associated setting. If your environment requires separate AGPM Servers for some or all domains, configure those additional AGPM Servers as exceptions to the default. If you do not centrally configure AGPM Server connections, each Group Policy administrator must manually configure the AGPM Server to be displayed for each domain.

-   [Configure an AGPM Server connection for all Group Policy administrators](#bkmk-defaultarchiveloc)

-   [Configure additional AGPM Server connections for all Group Policy administrators](#bkmk-additionalarchiveloc)

-   [Manually configure an AGPM Server connection for your account](#bkmk-manuallyconfigurearchiveloc)