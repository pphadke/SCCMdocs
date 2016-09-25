﻿---
title: "Update and retire applications | System Center Configuration Manager"
ms.custom: na
ms.date: 05/26/2016
ms.prod: configuration-manager
ms.reviewer: na
ms.suite: na
ms.technology: 
  - configmgr-app
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 68ac8a07-8e54-4a3c-91e3-e50dc1cabf5d
caps.latest.revision: 9
author: robstackmsft

---
# Update and retire applications with System Center Configuration Manager
Eventually, you will likely want to make changes to an application, uninstall it, or replace an already deployed application with a new application. System Center Configuration Manager includes the following capabilities to help you with this:  
  
-   **Revise applications** - When you make changes to an application or deployment type, Configuration Manager maintains a history of these changes. You can revert the application to a previous revision at any time. You can also view its properties, restore a previous revision of an application, or delete an old revision.  
  
     For more information, see [Application revisions](../../apps/deploy-use/revise-and-supersede-applications.md#BKMK_Rev).  
  
-   **Supersede applications** - Lets you upgrade or replace existing applications by using a supersedence relationship. When you supersede an application, you can specify a new deployment type to replace the deployment type of the superseded application and also configure whether to upgrade or uninstall the superseded application before the superseding application is installed.  
  
     For more information, see [Application supersedence](../../apps/deploy-use/revise-and-supersede-applications.md#BKMK_Super).  
  
-   **Uninstall applications** - Configuration Manager makes uninstalling an application easy. This can be accomplished silently, without any intervention from the end user.  
  
     For more information, see [How to uninstall applications](../../apps/deploy-use/uninstall-applications.md).  
  
