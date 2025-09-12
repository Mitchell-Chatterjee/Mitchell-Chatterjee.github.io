---
title: Migration to Agentic LLM Retrieval & Summarization
date: 2025-09-12
external_link: ''
featured: true
summary: Migration from a proprietary orchestration framework to Agno/LangChain, with real-time RAG and multimodal retrieval at scale.
---

## Overview

At JSI I led the migration from a proprietary orchestration framework to an agentic architecture using Agno and LangChain. The goal was to build a modular, LLM-based retrieval and summarization system integrated with MCP and deployable on-premises across customer sites.

## Problem

- Existing orchestration was monolithic and hard to maintain.
- Retrieval quality and latency at scale (billions of multimodal records) were poor for real-time operational use.

## Solution

- Adopted a modular agentic approach using Agno and LangChain for orchestration.
- Built streaming ingestion pipelines to embed audio, text, and images into a vector store (FAISS/HNSW).
- Implemented hybrid search (dense + sparse) and chunking strategies to improve recall and relevance.
- Added a summarization agent to synthesize results, and an evaluation pipeline (DeepEval + A/B) to measure relevance and latency.

## Architecture (high level)

1. Ingest: Kafka-based event ingestion for multimodal records
2. Preprocessing: audio → ASR → text; images → OCR/CLIP embeddings
3. Embeddings: per-modality encoders, unified vector representation
4. Vector Store: FAISS/HNSW with sharding for scale
5. Orchestration: Agno & LangChain agents sequence retrieval, grounding, summarization
6. Serving: on-prem deployments with GPU acceleration and autoscaling policies

## Results

- Served retrieval & summarization at low-latency for operational workflows
- Scaled to billions of records with near real-time updates
- Evaluated with DeepEval and A/B tests to tune models and rerankers

## Links

- Internal architectures and code available upon request.

