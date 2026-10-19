---
title: "Sentry: Real-Time Threat Detection"
summary: "Always-on detection over high-volume multimodal data streams, with an event-driven alerting architecture that cut notification latency by 33%."
date: 2019-05-01
weight: 2
tags: ["Anomaly detection", "Streaming", "Kafka"]
---

## Context

[Sentry](https://www.jsitelecom.com/2025/06/03/jsi-expands-digital-intelligence-platform-ai-driven-insights/) is the always-on detection component of JSI's 4Sight platform. Rather than waiting for an investigator to search, it continuously scans incoming and historical data for high-risk signals and raises alerts with supporting evidence.

## What I built

- **Real-time detection.** Designed and deployed a threat detection system that scans high-volume multimodal streams (audio, text, images, video) and flags high-risk activity using anomaly detection and proprietary ML models.
- **Event-driven alerting.** Proposed and implemented a Kafka-based, event-driven architecture for time-sensitive alerting workflows, reducing end-to-end notification latency by **33%**.

## Stack

{{< badges "Python, Kafka, Anomaly detection, HPC" >}}