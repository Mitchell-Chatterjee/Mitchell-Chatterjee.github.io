---
title: "Iris: Investigative AI Assistant"
summary: "Conversational, on-premises LLM assistant for digital investigations: agentic retrieval and summarization over billions of multimodal records."
date: 2024-01-01
weight: 1
tags: ["LLMs", "RAG", "Agents", "Evaluation"]
---

## Context

[Iris](https://www.jsitelecom.com/platform/4sight-ai-powered-investigations/) is the conversational assistant in JSI's 4Sight digital intelligence platform. Investigators ask questions in plain language and Iris searches across audio, text, and image evidence, summarizes what it finds, and supports follow-up questions. Everything runs on-premises and air-gapped: no data leaves the customer's site.

## What I built

- **Agentic retrieval and summarization.** Led the migration from a proprietary orchestration framework to Agno/LangChain, producing a modular agent system integrated with MCP.
- **Real-time multimodal RAG.** Built the pipeline that embeds and retrieves billions of audio, text, and image records, improving search latency and contextual relevance.
- **Evaluation framework.** Spearheaded the company-wide evaluation framework, using DeepEval and A/B testing to track relevance, latency, and interaction quality release over release.

## Scale

- Deployed on-premises across customer sites with 100+ GPUs
- Billions of multimodal records indexed for retrieval

## Stack

{{< badges "Python, PyTorch, Agno, LangChain, MCP, DeepEval, Kubernetes" >}}