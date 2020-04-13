---
title: Azure Monitor Logs reference - ADAssessmentRecommendation
description: Reference for ADAssessmentRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 3/16/2020
---

# ADAssessmentRecommendation

 Recommendations generated by AD assessments that are started through a scheduled task. When you schedule the assessment it runs by default every 7 days and upload the data into Azure Log Analytics

## Categories

- Workloads
## Solutions

- Active Directory Health Check
- ADAssessmentPlus
## Resource types

- Virtual machine




## Columns

|Column|Type|Description|
|---|---|---|
|SourceSystem|string|OpsManager|
|AssessmentId|string|ID of the assessment|
|RecommendationId|string|ID of the recommendation generated|
|Recommendation|string|Generated recommendation|
|Description|string|Description of the recommendation|
|RecommendationResult|string|Result of the recommendation generated|
|TimeGenerated|datetime|Date and time the record was created.|
|FocusAreaId|string|ID of the Focus Area|
|FocusArea|string|Area to be focussed on|
|ActionAreaId|string|ID generated for Action Area|
|ActionArea|string|The segment in which action is to be performed|
|RecommendationWeight|real|Weight of recommendation|
|Computer|string|The machine from which data is uploaded|
|AffectedObjectType|string|Type of object which is affected|
|AffectedObjectName|string|Name of the affected object|
|Forest|string||
|Domain|string|Domain of the system|
|DomainController|string||
|Technology|string||
|CustomData|string||
|Type|string||
|_ResourceId|string||