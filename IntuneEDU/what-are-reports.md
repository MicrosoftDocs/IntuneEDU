---
# required metadata

title: View and download reports in Intune for Education 
titleSuffix: Intune for Education
description: Get reports to help you understand device, settings, and application activity in Intune for Education.
keywords:
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/01/2021
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.subservice: education
ms.technology:
ms.assetid: a5922c35-261c-43db-9c7b-c5c93af9cbec
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: elcox
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# View and download reports

View your current device, application, setting, and health inventory in Intune for Education. Download reports to review or share offline.

This article describes the reports available and how to see them in Intune for Education.

## Device inventory
View all of your school's managed devices and device details. If a device is malfunctioning or hasn't received an app or setting, you can refer to this report to find out when it last checked-in with Intune.   

   ![The device inventory report screen, showing a list of devices under Intune for Education management.](./media/reports-001-device-inventory.png)

## Device actions
View all remote device actions that were initiated on managed devices. This report provides details such as Restart, Factory Reset, Autopilot Reset, and Rename actions that were initiated by an admin.

   ![The device action report screen, showing a list of devices under Intune for Education management.](./media/reports-002-device-actions.png)

## Application inventory
View all apps installed on the managed devices in your school. This report provides details that will help you troubleshoot deployment problems. See important details such as the number of devices the app belongs to and the current version installed.  
 
   ![The application inventory report screen, showing a list of apps under Intune for Education management.](./media/reports-003-app-inventory.png)  

## Settings errors
View a list of current setting errors and the groups affected. This report lists both the devices and users that have conflicting, unresolved settings.   

   ![The settings errors report screen, showing a list of setting conflicts.](./media/reports-004-settings-error.png)

## Windows Defender
View the Windows Defender device health status for every managed device in your school. This report lists a device health status to alert you to devices that are not fully secure.

   ![The Windows Defender report screen, showing a list of devices reported by Windows Defender Antivirus.](./media/reports-005-windows-defender.png)
   
## Autopilot deployment
View the Windows Autopilot report for your tenant. This report provides a list of managed Autopilot devices and current enrollment state.

   ![The Windows Autopilot report, showing a list of devices under Intune for Education management.](./media/reports-006-autopilot-deplopyment.png)
   
## Access your reports

1. From the [Intune for Education dashboard](https://intuneeducation.portal.azure.com), click **Reports**.  
2. Select the report you want to view. 
3. Use the search boxes to find specific devices, applications, and settings.
4. To download a report, click **Download report**. Intune for Education will download a report to your computer, as a comma-separated value (.csv) file. View and modiy the file in a spreadsheet app, such as [Microsoft Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba).  

## Next steps  
Find out more about the [full reporting experience in Intune](https://docs.microsoft.com/mem/intune/fundamentals/reports) or about reporting [using Microsoft Graph](https://developer.microsoft.com/graph/docs/overview/overview).
