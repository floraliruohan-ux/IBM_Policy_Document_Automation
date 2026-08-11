# IBM Policy Document Automation (EPLC Project)

`AI` · `RAG` · `LLM` · `Embeddings` · `Python` · `Data Engineering`

This repository presents selected work from my IBM Enterprise Performance Life Cycle (EPLC) practicum. Due to project confidentiality, only representative non-sensitive materials are included.

## Project Overview

Our team developed an AI-assisted prototype for retrieving policy information and generating draft EPLC document sections.

My work focused on preparing policy documents for downstream AI use by converting unstructured files into structured data, generating subsection-level embeddings, and analyzing document characteristics to improve chunking and retrieval.

## AI Collaboration

I used AI throughout the workflow to support code generation, debugging, document structuring, data processing, and iterative problem solving.

I defined the data logic and validation criteria, reviewed AI-assisted outputs, and integrated the results into the final data pipeline.

## My Role

- Converted policy templates into hierarchical JSON for machine-readable retrieval
- Built subsection-level embeddings using `multilingual-e5-base`
- Supported vector retrieval and RAG-ready data preparation
- Analyzed document length and chunk distributions to guide retrieval design
- Collaborated with GenAI and UX teams on the AI-assisted prototype

## AI / Data Workflow

**Policy Documents → Cleaning → Structured JSON → Chunking → Embeddings → Vector Retrieval → RAG → AI Assistant**

## Repository Structure

```text
IBM_Policy_Document_Automation/
│
├── README.md
│
├── examples/
│   ├── EPLC_SLA_MOU_Template.doc
│   ├── EPLC_SLA_MOU_Template.json
│   ├── EPLC_Data_Conversion_Plan_Template.doc
│   └── EPLC_Data_Conversion_Plan_Template.json
│
├── embedding/
│   ├── eplc_embedding_pipeline.ipynb
│   └── data_conversion_plan_embeddings.json
│
└── analysis/
    ├── Exploratory_Data_Analysis.pdf
    └── Data_Visualization.pdf
```

## Key Takeaway

This project showed that reliable enterprise AI depends not only on model capability, but also on data quality, document structure, chunking, metadata, retrieval design, and human validation.

The experience strengthened my understanding of how data engineering and AI can work together to turn complex policy documents into usable knowledge systems.

**Ruohan Li**  
[LinkedIn](www.linkedin.com/in/ruohanli-flora0930) 
