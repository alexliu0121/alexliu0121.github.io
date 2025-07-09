---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: NLP Software Developer
    company: UCSC
    company_url: 'https://www.ucsc.edu/'
    company_logo: custom/UCSC
    location: Santa Clara, California
    date_start: '2025-02-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Spearheaded new CruzChat features, boosting active-session stability 35% by expanding unit-test coverage and automating GitHub Actions CI pipelines.
        * Prototyped Large-Language-Model classroom tools, cutting pilot turnaround from 3 weeks to 5 days through close collaboration with faculty and LangChain/Python rapid-prototyping.
        * Diagnosed and Resolved production incidents with < 1-day MTTR, sustaining > 99% uptime via Azure monitoring, log analysis, and hot-fix deployments.

  - title: Machine Learning Engineer Intern
    company: Adobe
    company_url: 'https://www.adobe.com/'
    company_logo: custom/adobe
    location: Santa Clara, California
    date_start: '2024-03-01'
    date_end: '2024-12-31'
    description: |2-
        Responsibilities include:
        
        * Co‑designed a multi‑agent summarization framework that coordinates GPT‑4o, LLaMA‑3, and Claude, delivering 2× ROUGE‑1 gains vs. single‑model baselines on ArXiv & GovReport corpora.
        * Implemented a multi-stage chunking + re-summarization pipeline, reducing long-document latency by 42% while preserving factual consistency through dynamic context-window optimization.
        * Led prompt‑optimization sweeps and built evaluation dashboards that quantified cost-performance trade-offs, trimming Azure OpenAI spend by 28% per experiment.
        * Contributed to internal research presentations and conference paper submissions.

  - title: Research Assistant
    company: Computational Biology & Intelligence System Lab
    company_url: 'https://cobis.bme.ncku.edu.tw/thyang/Main' 
    company_logo: custom/academic-cap
    location: Taiwan
    date_start: '2021-01-01'
    date_end: '2022-01-01'
    description: |2-
        Responsibilities include:
        
        * Built a web‑scraping and NLP pipeline that mined 200 k+ biomedical abstracts, driving an 83%-F1 BERT classifier for transcription-factor/ gene extraction via fine-tuning in PyTorch.
        * Benchmarked IRES-prediction tools with ROC analysis and integrated the model into the public Human IRES Atlas database. 

design:
  columns: '1'
---
