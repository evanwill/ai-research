---
section: Tools
nav_order: 3
title: AI Tools
topics: 
---


- Specialized Academic AI (Consensus, Elicit, Undermind): These platforms bypass general chat interfaces to search directly across scientific literature databases. They excel at paper discovery, extracting methodology-level details, and synthesizing cross-study consensus.
- Generalist Campus LLMs (Claude, Gemini, ChatGPT): While highly capable of processing long-context documents and translating dense academic jargon, they do not inherently search scholarly databases unless specifically prompted or tethered to a retrieval tool. They are best utilized for brainstorming, refining research questions, and generating Boolean strings.


Considerations:

- what sources do they search or have access to?
- privacy
- bias
- cost
- design

- primo Research Assistant, https://alliance-uidaho.primo.exlibrisgroup.com/discovery/login?vid=01ALLIANCE_UID:UID
- Vandal Chat, https://chat.uidaho.edu/
    - https://mindrouter.uidaho.edu/blog/introducing-vandalchat-deep-research
    - AI chat assistant powered by MindRouter. It is great for drafting and editing writing, explaining concepts, summarizing and asking questions about your documents, working with data, writing code, brainstorming, and translating.​
    - VandalChat Deep Research is a first-pass research assistant intended to help users discover sources, understand a topic, and identify avenues for further investigation. Its reports are not peer reviewed and should not be treated as authoritative research. Every factual claim and citation should be independently verified before use in scholarship, proposals, publications, or decision-making. You are responsible and accountable for how the report is interpreted, applied, cited, or incorporated into subsequent work.
    - VandalChat does not have any special access to U of I information, policies, procedures, etc. at this point, but it might in the future​
- MindRouter, https://mindrouter.uidaho.edu/
    - University of Idaho’s own generative AI service. Anyone with a Vandal account can sign in. It runs on University hardware and is managed by Research Computing and Data Services, so no data is sent to non-campus entities.​
- Ai2 Asta, https://asta.allen.ai/
    -  scholarly research assistant that combines literature understanding and data-driven discovery. Asta uses 108M+ abstracts and 12M+ full-text papers to find, summarize, and analyze scientific evidence
- Research Rabbit, https://www.researchrabbit.ai/
    - online tool that helps you discover research faster, stay organized, and build a deeper understanding of your field.1 By following citation trails, who a paper cites, and who cites it in turn, you can uncover the full landscape of literature in your field
    - search from an article, link to zotero library, keyword search


broad types: general purpose generative models vs. specialized, research-grade retrieval-augmented generation (RAG) platforms
general llms risk = hallucination. RAGs attempt to ground in real research
challenge = reproducible search strategies

databases -- generate boolean using ai from plain language


Based on recent surveys and reports from 2024-2025, here are the most widely used AI research tools in academia:

## General-Purpose LLMs Dominate

Across multiple studies (Nature/Wiley "AI for Science" report, Paperpile survey of 1,800+ researchers), **general-purpose chatbots account for roughly 76-80% of all tool mentions**, far outpacing specialized research tools:

| Tool | Usage Rate | Notes |
|---|---|---|
| **ChatGPT** | ~37% of mentions; leads by wide margin | Used across literature review, writing, coding |
| **Gemini** | ~19% | Second-most used; integrated with Google Scholar |
| **Claude** | ~7% | Popular for long-form document analysis |
| **Copilot** | ~11% increase YoY | Strong for code-related research |
| **Perplexity** | Growing | Search-focused with citations |

Regional variations matter: DeepSeek reached 78% usage among Chinese researchers by early 2026, but is less adopted elsewhere.

## Specialized Research Tools

These serve narrower functions but remain far less known (average awareness ~11% per tool):

| Category | Tool | Primary Use |
|---|---|---|
| Literature discovery | **Elicit** | Extracts data across papers; builds comparison tables |
| Literature discovery | **Consensus** | Answers questions with confirming/opposing evidence from 200M+ papers |
| Literature mapping | **ResearchRabbit** | "Spotify for papers" — visualizes citation networks |
| Citation verification | **Scite** | Shows whether citations support or contradict claims |
| Writing assistance | **Paperpile** | Reference management with AI features |
| Code/data | **Jupyter AI / Copilot** | In-notebook assistance for computational research |
| Summarization | **Semantic Scholar** | AI-powered paper recommendations |
| Knowledge synthesis | **NotebookLM** | Upload sources and chat with your corpus |

## Why the Gap?

The Wiley study noted that **only 25% of researchers have used specialized science AI tools** versus 80% for general-purpose ones. The barrier isn't capability—it's awareness and accessibility. Researchers default to tools they already know.

## What This Means for Information Literacy

Given that most academics use general chatbots first, the debiasing checklist I shared earlier becomes essential. ChatGPT won't flag its own hallucinations, won't show you dissenting viewpoints unless prompted, and presents uncertain claims with fluent confidence—all amplification risks for automation bias, confirmation bias, and fluency illusions.

Specialized tools like Scite and Consensus help mitigate some of these risks by grounding answers in verifiable literature, but they're still subject to garbage-in-garbage-out (question framing matters) and don't eliminate the need for primary source verification.


https://www.nature.com/immersive/partnercontent/fudan/aiforscience/chapter-2-ai-tools-in-research.html
https://www.wiley.com/en-us/about-us/ai/study/researchers


-----------

VandalChat 

- deep research mode, craft a query, get a PDF report back, emailed later
