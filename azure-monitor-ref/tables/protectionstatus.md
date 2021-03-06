---
title: Azure Monitor Logs reference - ProtectionStatus
description: Reference for ProtectionStatus table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 4/30/2020
---

# ProtectionStatus

 Antimalware installation info and security health status of the machine:

## Categories

- Security
## Solutions

- Antimalware Assessment
- Security and Audit
- SecurityCenter
- SecurityCenterFree
## Resource types

- Virtual machine
- Virtual machine scale set




## Columns

|Column|Type|Description|
|---|---|---|
|AMProductVersion|string||
|Computer|string||
|ComputerEnvironment|string||
|ComputerIP_Hidden|string||
|DetectionId|string||
|DeviceName|string||
|ManagementGroupName|string||
|ProtectionStatus|string||
|ProtectionStatusDetails|string||
|ProtectionStatusRank|int||
|Resource|string||
|ResourceGroup|string||
|_ResourceId|string||
|ResourceId|string||
|ResourceProvider|string||
|ResourceType|string||
|ScanDate|datetime||
|SignatureVersion|string||
|SourceComputerId|string||
|SourceSystem|string||
|SubscriptionId|string||
|TenantId|string||
|Threat|string||
|ThreatStatus|string||
|ThreatStatusDetails|string||
|ThreatStatusRank|int||
|TimeGenerated|datetime||
|Type|string||
|TypeofProtection|string||
|VMUUID|string||
