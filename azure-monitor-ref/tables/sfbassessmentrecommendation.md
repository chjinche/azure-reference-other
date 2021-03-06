---
title: Azure Monitor Logs reference - SfBAssessmentRecommendation
description: Reference for SfBAssessmentRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 3/16/2020
---

# SfBAssessmentRecommendation

 Recommendations generated by Skype for Business assessments that are started through a scheduled task. When you schedule the assessment it runs by default every 7 days and upload the data into Azure Log Analytics

## Categories

- Workloads
## Solutions

- SfBAssessment




## Columns

|Column|Type|Description|
|---|---|---|
|SourceSystem|string||
|AssessmentId|string||
|RecommendationId|string||
|Recommendation|string||
|Description|string||
|RecommendationResult|string||
|TimeGenerated|datetime||
|FocusAreaId|string||
|FocusArea|string||
|ActionAreaId|string||
|ActionArea|string||
|RecommendationWeight|real||
|Computer|string||
|AffectedObjectType|string||
|AffectedObjectName|string||
|Forest|string||
|Domain|string||
|LyncOrganization|string||
|LyncInternalDomain|string||
|LyncSimpleURLDomain|string||
|LyncSite|string||
|LyncFEPool|string||
|LyncFrontEnd|string||
|LyncCentralMgmtStoreDatabase|string||
|LyncUserStoreDatabase|string||
|Technology|string||
|CustomData|string||
|Type|string||
