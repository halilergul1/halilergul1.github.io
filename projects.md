---
layout: page
title: Projects
---

<style>
  .project-card {
    background: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 10px;
    padding: 1.5rem 1.8rem;
    margin-bottom: 1.5rem;
    box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  }
  .project-card h3 {
    margin-top: 0;
    margin-bottom: 0.5rem;
    font-size: 1.15rem;
  }
  .project-card p {
    font-size: 0.93rem;
    color: #444;
    margin-bottom: 0.8rem;
  }
  .badge-list {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-bottom: 0.9rem;
  }
  .tech-badge {
    background: #e8f4f8;
    color: #0085A1;
    border-radius: 12px;
    padding: 0.2rem 0.75rem;
    font-size: 0.78rem;
    font-weight: 600;
  }
</style>

<div class="project-card">
  <h3>RAG-based Question-Answer System</h3>
  <p>
    A production-ready retrieval-augmented generation pipeline built for document-heavy use cases. The system ingests PDFs, performs semantic chunking, and indexes content into an ElasticSearch vector store. At query time, it retrieves the most relevant passages and synthesises answers with full source citations — all served through a clean FastAPI endpoint. Designed to be dropped into any document-heavy workflow.
  </p>
  <div class="badge-list">
    <span class="tech-badge">LlamaIndex</span>
    <span class="tech-badge">ElasticSearch</span>
    <span class="tech-badge">FastAPI</span>
    <span class="tech-badge">Docker</span>
    <span class="tech-badge">OpenAI</span>
  </div>
  <a href="https://github.com/halilergul1/QA-app" target="_blank" class="btn btn-primary btn-sm">View on GitHub</a>
</div>

<div class="project-card">
  <h3>LLM Fine-Tuning with PEFT</h3>
  <p>
    A lightweight, extensible toolkit for supervised fine-tuning of open-source large language models using parameter-efficient methods. Leverages LoRA via Unsloth for memory-efficient training and supports any HuggingFace causal model out of the box. Inference is optimised with vLLM for high-throughput serving. A practical starting point for anyone looking to adapt a foundation model to a specialised domain without burning GPU budget.
  </p>
  <div class="badge-list">
    <span class="tech-badge">LLaMA3</span>
    <span class="tech-badge">LoRA</span>
    <span class="tech-badge">Unsloth</span>
    <span class="tech-badge">Hugging Face Transformers</span>
    <span class="tech-badge">vLLM</span>
  </div>
  <a href="https://github.com/halilergul1/Fine-Tuning-LLM" target="_blank" class="btn btn-primary btn-sm">View on GitHub</a>
</div>

<div class="project-card">
  <h3>NLP-Powered Hotel Recommendation System</h3>
  <p>
    A two-stage recommendation engine built for Turkish-language hotel data. The first stage retrieves candidate hotels using cosine similarity over BERTopic embeddings of property descriptions. The second stage re-ranks candidates by a composite popularity score incorporating review signals. The system achieves 75% geographically relevant results — a meaningful improvement over keyword-based baselines — and demonstrates the value of topic-aware embeddings for low-resource languages.
  </p>
  <div class="badge-list">
    <span class="tech-badge">BERTopic</span>
    <span class="tech-badge">Turkish NLP (Zemberek)</span>
    <span class="tech-badge">Cosine Similarity</span>
    <span class="tech-badge">Python</span>
  </div>
  <a href="https://github.com/halilergul1/nlp-reco" target="_blank" class="btn btn-primary btn-sm">View on GitHub</a>
</div>

<p style="margin-top: 1.5rem; font-size: 0.92rem;">
  See all projects on <a href="https://github.com/halilergul1" target="_blank">GitHub →</a>
</p>
