---
title: v0.8.42 Armory Agent Clouddriver Plugin (2022-01-28)
toc_hide: true
version: 00.08.42

---

## Improvements
* Optimized performance of "GET /applications/{application}/serverGroups" request for large number of results, by splitting big queries into multiple smaller ones.

## Changes
* Response of "GET /armory/agents" replaces the "connected" field by "clouddriverAlive", which better represents the meaning of the entry. 
