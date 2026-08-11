# IBM Policy Document Automation (EPLC Project)

This repository presents a representative example of my work from the IBM Enterprise Policy Lifecycle (EPLC) practicum. Due to project confidentiality, only selected non-sensitive materials and examples are included.

## Project Overview

The project explored how unstructured U.S. government policy documents can be transformed into structured, machine-readable data to support AI-powered retrieval and RAG-based question answering.

Using policy documents from the U.S. Department of Health and Human Services (HHS), I analyzed document structures, metadata patterns, and retrieval requirements to support the development of an enterprise AI Assistant.

## My Role

- Analyzed policy document structures and identified key metadata fields for downstream AI retrieval
- Built Python-based workflows for document parsing, structuring, and data preprocessing
- Supported the design of a RAG pipeline combining document embeddings, vector retrieval, and LLM-based question answering
- Designed and tested prompts and evaluated model outputs across accuracy, consistency, and retrieval quality

## AI / Data Workflow

**Policy Documents → Parsing & Structuring → Metadata Extraction → Embeddings → Vector Retrieval → RAG → AI Assistant**

The workflow was designed to improve the accessibility and retrievability of policy information while maintaining traceability to original source documents.

## Representative Work

### Exploratory Data Analysis
`Exploratory Data Analysis.docx`

Analyzed the accessibility, structure, and metadata potential of multiple HHS policy sources to assess their readiness for automated processing and retrieval.

### Policy Document Structuring
`EPLC_SLA_MOU_Template.doc`

A representative Service Level Agreement / Memorandum of Understanding document from the EPLC policy archive.

### Structured Metadata
`EPLC_SLA_MOU_Template.json`

Converted the original policy document into a structured JSON representation containing extracted sections and hierarchical metadata for downstream retrieval.

## Why RAG?

RAG was selected because policy documents are frequently updated and answers need to remain grounded in traceable source materials. Compared with relying solely on model fine-tuning, retrieval-based generation allows the knowledge base to be updated more efficiently while improving source transparency.

## AI Collaboration

I used LLMs throughout the workflow to assist with code generation, document structuring, metadata extraction, prompt iteration, and debugging. I defined the processing logic and evaluation criteria, then reviewed and validated AI-generated outputs before incorporating them into the final pipeline.

## Key Takeaway

This project showed me that successful enterprise AI applications depend not only on model capability, but also on document structure, data quality, retrieval design, and evaluation. The quality of the underlying knowledge pipeline directly shapes the reliability of the final AI experience.

## Tech Stack

`Python` · `RAG` · `LLM` · `NLP` · `Embeddings` · `Vector Retrieval` · `Prompt Engineering` · `JSON`

## Author

**Ruohan Li**

LinkedIn: [ruohanli-flora0930](YOUR_LINKEDIN_URL)
