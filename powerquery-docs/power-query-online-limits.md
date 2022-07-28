---
title: Power Query Online Usage Limits
description: Authoring and refresh limits for Power Query Online in its various product integrations.
author: cpopell


ms.topic: conceptual
ms.date: 2/28/2022
ms.author: dougklo

LocalizationGroup: reference
---

# Power Query Online Limits

## Summary


Power Query Online is integrated into a variety of Microsoft products. Since these products target different scenarios, they may set different limits for Power Query Online usage.

Limits are enforced at the beginning of query evaluations. Once an evaluation is underway, only timeout limits are imposed.

### Limit Types

Hourly Evaluation Count: The maximum number of evaluation requests a user can issue during any 60 minute period

Daily Evaluation Time: The net time a user can spend evaluating queries during any 24 hour period

Concurrent Evaluations: The maximum number of evaluations a user can have running at any given time

### Authoring Limits

Authoring limits are the same across all products. During authoring, query evaluations return previews that may be subsets of the data. Data is not persisted.

Hourly Evaluation Count: 1000

Daily Evaluation Time: Currently unrestricted

Per Query Timeout: 10 minutes

### Refresh Limits

During refresh (either scheduled or on-demand), query evaluations return complete results. Data is typically persisted in storage.

| Product Integration | Hourly Evaluation Count (#) | Daily Evaluation Time (Hours) | Concurrent Evaluations (#) |
|--|--|--|--|
| Microsoft Flow (SQL Connector&mdash;Transform Data Using Power Query) | 500 | 2 | 5 |
| Dataflows in PowerApps.com (Trial)| 500 | 2 | 5 |
| Dataflows in PowerApps.com (Production) | 1000 | 8 | 10 |
| Data Integration in PowerApps.com Admin Portal | 1000 | 24 | 10 |
| Dataflows in PowerBI.com | 1000 | 100 | 10 |
