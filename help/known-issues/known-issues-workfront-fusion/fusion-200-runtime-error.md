---
title: 'Workfront Fusion: RuntimeError with 200 response from Workfront module'
description: A Workfront module can return a `RuntimeError [200]` response. The 200 implies a successful response, but the error shows that the request was unsuccessful.
hidefromtoc: yes
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
---
# Workfront Fusion: RuntimeError with 200 response from Workfront module

A Workfront module can return a `RuntimeError [200]` response. The 200 implies a successful response, but the error shows that the request was unsuccessful.

This may occur if the response is extremely long. The data is returned to Fusion, but cannot be processed by Fusion.

_First reported on January 3, 2024._
