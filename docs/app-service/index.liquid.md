---
title: App Service | Reference Architectures | Azure | Microsoft Docs
description: Recommended architectures for a web applications running in Microsoft Azure.
services: app-service,app-service\web,sql-database
documentationcenter: na
author: MikeWasson
manager: christb
editor: ''
tags: ''
layout: RefArchSeriesPage

ms.assetid: c7022bbb-b2fd-43f4-a557-6b511b79dd10
ms.service: guidance
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 10/26/2016
ms.author: mwasson

series_title: Build web applications with Azure App Service
columns: 3
articles:
  - id: basic-web-app
    title: Basic web application
    description: A basic web application using App Service plus Azure SQL Database.
  - id: scalable-web-app
    title: Scalable web application
    description: Improves performance and scalability by using services such as Azure Redis Cache, Azure CDN, and WebJobs.
  - id: multi-region-web-app
    title: Multi-region web application
    description: Improves availability by running in multiple regions, using Traffic Manager to fail over if the primary region goes down.
---

Azure App Service is a fully managed cloud service for hosting web applications and web APIs. However, most applications require more than just a web tier. For example, a typical application may use a database, cache, or CDN. Other considerations include deployment, diagnostics, and monitoring.

{% include 'series' with articles %}