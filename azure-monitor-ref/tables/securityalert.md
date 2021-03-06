---
title: Azure Monitor Logs reference - SecurityAlert
description: Reference for SecurityAlert table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 3/16/2020
---

# SecurityAlert

 Alerts that been generated by security products.

## Categories

- Security
## Solutions

- AzureSecurityOfThings
- Security and Audit
- SecurityCenter
- SecurityCenterFree
- SecurityInsights




## Columns

|Column|Type|Description|
|---|---|---|
|TimeGenerated|datetime||
|DisplayName|string||
|AlertName|string||
|AlertSeverity|string||
|Description|string||
|ProviderName|string||
|VendorName|string||
|VendorOriginalId|string||
|SystemAlertId|string||
|ResourceId|string||
|SourceComputerId|string||
|ConfidenceLevel|string||
|ConfidenceScore|real||
|IsIncident|bool||
|StartTime|datetime||
|EndTime|datetime||
|ProcessingEndTime|datetime||
|RemediationSteps|string||
|ExtendedProperties|string||
|Entities|string||
|WorkspaceSubscriptionId|string||
|WorkspaceResourceGroup|string||
|ExtendedLinks|string||
|ProductName|string||
|ProductComponentName|string||
|AlertLink|string||
|Type|string||
