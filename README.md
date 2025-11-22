# LORIE

**Local Offline Reasoning Intelligence Engine**

> LORIE is a personal offline LLM system: a unified reasoning and retrieval engine that runs entirely on local hardware. It uses a curated knowledge corpus, embeddings, domain routing, and tool modules to generate detailed, cross-domain answers without the cloud.

## Core Features
  - Domain-aware router for history, psychology, sociology, medicine - first aid, coding, technology, math, mechanics, animals and husbandry, land and gardening, DIY, engineering basics, ancient history, anthropology, forensics, and more.
  - Retrieval-Augmented Generation (RAG) using local documents.
  - Deductive and cross-domain reasoning engine.
  - Metadata scoring, weighting, and relevance ranking.
  - Verification layer (consistency checks and contradiction filters).
  - Persona layer that adapts to personal tone, clarity, and reasoning style.
  - Local model loader for GGUF, Ollama, and quantized LLMs.
  - PyQt6 desktop interface and FastAPI backend for clean separation of UI and logic.

## Goals
  - Provide ChatGPT-like reasoning fully offline.
  - Remain usable during outages, travel, camping, or emergency conditions.
  - Serve as a long-term, expandable personal knowledge system.
  - Remain fast and responsive on consumer-grade hardware.
  - Support ingestion of books, PDFs, notes, images (OCR), and transcripts.

## Status
- Active development.
- Current baseline release: v0.1.0.
