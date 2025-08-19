# AI Co-pilot for Investment Analysis (In Progress)

This repository contains the code, data, and research for my personal project to build a sophisticated AI analyst.

## Project Goal
The objective is to build a specialized AI system that can ingest a 100+ page corporate annual report and generate a comprehensive, multi-page summary of a company's financial health, competitive moat, and strategic risks, similar to the workflow of a junior financial analyst.

## Key Achievements to Date
* **Data Curation & Engineering:** Single-handedly curated a world-class, diverse dataset of **over 100 expert-level lessons**. This curriculum spans multiple industries (tech, auto, media, Indian conglomerates) and company profiles (market leaders, startups, loss-making entities) to train a robust and unbiased AI analyst.
* **Advanced AI Instruction Design:** Developed a sophisticated curriculum to teach a base LLM advanced skills beyond simple summarization, including **comparative analysis, management tone classification, and financial red flag identification**.
* **Fine-Tuning Strategy:** Designed and implemented a fine-tuning strategy using state-of-the-art, resource-efficient techniques (**QLoRA**) to specialize the `google/gemma-2b-it` model for the niche domain of financial analysis.

## Tech Stack
* **Model:** `google/gemma-2b-it`
* **AI Libraries:** Hugging Face (`transformers`, `datasets`, `peft`), QLoRA, `bitsandbytes`, PyTorch
* **Data & Logic:** Python, Pandas

## Current Status
* **Phase 1 (Data Curation):** 100% Complete. The master dataset is finalized.
* **Phase 2 (Fine-Tuning):** Ready for execution. The master training script is complete and tested, pending GPU availability for the final, long-running training job.
* **Phase 3 (Application Logic):** Core components (Rules Engine, Data Fetcher) are built and tested.

---
