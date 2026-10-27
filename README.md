# Jialin Chen

I am an undergraduate student in Artificial Intelligence at The Hong Kong University of Science and Technology (Guangzhou), 2023–2027, including an exchange term at the University of Bologna from September 2025 to January 2026. I work on LLM reasoning, information retrieval, and retrieval-augmented generation. Email: [jchen380@connect.hkust-gz.edu.cn](mailto:jchen380@connect.hkust-gz.edu.cn).

## Research Interests

- LLM reasoning, including chain-of-thought and theory-of-mind prompting
- Retrieval-augmented generation for specialized documents
- Hybrid information retrieval with sparse and dense rankers
- Language-model agents grounded in task or scene context

## Selected Projects

### RAG-Based Pediatric Case Analysis

Built a hybrid retrieval pipeline using BM25, BGE-M3, and reciprocal rank fusion for pediatric medical literature retrieval. Developed query optimization for medical term mapping, negation preservation, and multi-query reformulation.

### Emotion-Aware Music Reasoning

[EmotiCompanion](https://github.com/ZuriZHAO/AIAA3800_Proj) is a group course project. I implemented the reasoning and music-generation modules.

The module turns a fused emotion and fatigue state into a music description, comparing a direct emotion map with a theory-of-mind and two-stage chain-of-thought procedure, and synthesizes audio with MusicGen. If the language-model API is unavailable, generation uses the rule-based prompt.

### Bologna Plaza Tour Guide

Private repository. It will not appear on this profile until the repository is public.

A Unity scene for walking through Piazza Maggiore and talking with a tour guide. A local FastAPI service calls an OpenAI-compatible chat model, resolves landmark identifiers on the server, and keeps the API key out of the Unity client. A keyword mock mode runs without a model.

### FaceNet Recognition Baseline

[AIAA 4313 project](https://github.com/yxiao986/AIAA4313_PROJECT) is a group course project. I implemented the recognition baseline.

The baseline detects a face, embeds it with FaceNet, matches the embedding to an enrollment set, and serves query and embedding calls through a local API.

## Technical Background

- Programming: Python, C#
- Machine learning: PyTorch, Hugging Face Transformers
- Information retrieval: BM25, BGE-M3, reciprocal rank fusion
- Tools: Git, FastAPI, Unity
