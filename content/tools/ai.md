---
section: Tools
nav_order: 3
title: AI Tools
topics: 
---

General purpose AI chatbots are good at basic summarizing, translating jargon, brainstorming, refining research questions, and generating keywords for traditional search tools.

- Specialized Academic AI: These platforms bypass general chat interfaces to search directly across scientific literature databases. They excel at paper discovery, extracting methodology-level details, and synthesizing cross-study consensus.
- Generalist Campus LLMs (Claude, Gemini, ChatGPT): While highly capable of processing long-context documents and translating dense academic jargon, they do not inherently search scholarly databases unless specifically prompted or tethered to a retrieval tool. They are best utilized for brainstorming, refining research questions, and generating Boolean strings.

broad types: general purpose generative models vs. specialized, research-grade retrieval-augmented generation (RAG) platforms
general llms risk = hallucination. RAGs attempt to ground in real research
challenge = reproducible search strategies

databases -- generate boolean using ai from plain language

## General-Purpose LLMs 

Most people are now familiar with general purpose AI chat interfaces, such as those from the major platforms:

- [Anthropic Claude AI](https://claude.ai/)
- [Google Gemini](https://gemini.google.com/)
- [OpenAI ChatGPT](https://chatgpt.com/)
- [Proton Lumo](https://lumo.proton.me/) - privacy focused platform, using a variety of open models.
- [Microsoft Copilot](https://copilot.com/) - uses other models integrated into Microsoft 365 ecosystem. Accessible via [U of I account](https://support.uidaho.edu/TDClient/40/Portal/KB/Article/3610/How-to-access-Microsoft-Copilot).
- [Perplexity AI](https://www.perplexity.ai/) - less of a general purpose tool, it uses other models in an answer and research focused tool with citation of sources.

### Vandal Chat

U of I maintains its own "sovereign" AI infrastructure running on University hardware and managed by Research Computing and Data Services, so no data is sent to non-campus entities.​
Advanced users can access it via the [MindRouter](https://mindrouter.uidaho.edu/) interface to set up APIs. 
However, a general purpose AI chat assistant interface is available:

[Vandal Chat](https://chat.uidaho.edu/){:.btn .btn-lg .btn-primary}

Features:

- It is great for drafting and editing writing, explaining concepts, summarizing and asking questions about your documents, working with data, writing code, brainstorming, and translating.​
- Deep Research is a first-pass research assistant intended to help users discover sources, understand a topic, and identify avenues for further investigation. Craft your query, give it time to work--you will get emailed a PDF report later.
- VandalChat does not have any special access to U of I information, policies, procedures, etc. or the Library's resources.

## Specialized Research Tools

These serve narrower functions but remain far less known (average awareness ~11% per tool):

Undermind


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


- Ai2 Asta, https://asta.allen.ai/
    -  scholarly research assistant that combines literature understanding and data-driven discovery. Asta uses 108M+ abstracts and 12M+ full-text papers to find, summarize, and analyze scientific evidence
- Research Rabbit, https://www.researchrabbit.ai/
    - online tool that helps you discover research faster, stay organized, and build a deeper understanding of your field.1 By following citation trails, who a paper cites, and who cites it in turn, you can uncover the full landscape of literature in your field
    - search from an article, link to zotero library, keyword search

- primo Research Assistant, https://alliance-uidaho.primo.exlibrisgroup.com/discovery/login?vid=01ALLIANCE_UID:UID

ChatGPT won't flag its own hallucinations, won't show you dissenting viewpoints unless prompted, and presents uncertain claims with fluent confidence—all amplification risks for automation bias, confirmation bias, and fluency illusions.


https://www.nature.com/immersive/partnercontent/fudan/aiforscience/chapter-2-ai-tools-in-research.html
https://www.wiley.com/en-us/about-us/ai/study/researchers

