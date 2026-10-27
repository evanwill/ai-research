---
section_id: Strategies
nav_order: 3
title: Research Strategies
topics: 
---

For a live workshop evaluating these platforms head-to-head, students must learn to treat AI not as a traditional search engine, but as an interpreter whose outputs require lateral verification


- Specialized Academic AI (Consensus, Elicit, Undermind): These platforms bypass general chat interfaces to search directly across scientific literature databases. They excel at paper discovery, extracting methodology-level details, and synthesizing cross-study consensus.
- Generalist Campus LLMs (Claude, Gemini, ChatGPT): While highly capable of processing long-context documents and translating dense academic jargon, they do not inherently search scholarly databases unless specifically prompted or tethered to a retrieval tool. They are best utilized for brainstorming, refining research questions, and generating Boolean strings.


| Research Task | AI / LLM Platforms | Traditional Databases |
| --- | --- | --- |
| Initial Discovery | Excels at natural language queries and mapping broad conceptual relationships. | Requires precise Boolean logic and exact keyword matching. |
| Literature Synthesis | Summarizes trends across multiple papers and extracts specific methodologies. | Returns isolated abstracts; synthesis is entirely manual. |
| Systematic Reviews | Unreliable due to hidden retrieval algorithms and inability to ensure exhaustive recall. | Essential. Provides reproducible search histories and rigorous limiters. |
| Access & Scope | Heavily biased toward Open Access research and recent works; frequently blind to recent paywalled articles. | Provides guaranteed access to institutional subscriptions and historical archives. |


The report identifies significant performance limitations, particularly in citation accuracy, where general-purpose models frequently generate fabricated or inaccurate references. In contrast, specialized platforms that link claims to specific sources reduce this risk. The evidence shows that verification requires distinct tests for existence and support, with practical workflows involving lateral reading, DOI resolution, and cross-referencing with independent sources.
the field is characterized by a growing reliance on AI for exploratory search and drafting, yet a persistent need for human oversight to detect errors and biases. The report found that hallucinated citations are becoming more prevalent, often disproportionately affecting early-career researchers and reinforcing existing inequities in scientific recognition. For information literacy workshops, the findings suggest that educators must position AI tools as supports rather than replacements for critical reasoning. Students are advised to treat AI outputs as unverified

Misattribution and Synthesis Errors: While models hallucinate fake citations less frequently than they used to, they still routinely misattribute a real claim to the wrong author, or confidently generate a summary that contradicts the actual findings of the cited paper.


lots of change, but the fundamental skills of the research process remain the same. 
information literacy, evaluating information


- Lateral Verification: Require students to take an AI-generated summary and run its citations back through a traditional database to verify publication status, context, and accuracy.
- Interrogating the Algorithm: Teach students to ask the model about its own blind spots (e.g., prompting the AI with, "What perspectives, methodologies, or data might be excluded from this summary?").
- Evaluating the Interpretation: The core of modern information literacy is recognizing that students are no longer just evaluating a primary source—they are evaluating the AI's interpretation of that source.

https://about.ebsco.com/blogs/ebscopost/ai-literacy-information-literacy-helping-students-navigate-new-research-landscape
https://crln.acrl.org/index.php/crlnews/article/view/26704/34626

- prompt as iterative process. research questions evolve. prompt engineering is same as basic research skills. 
- literacy framework --> searching for and evaluating information
    - Scholarship as Conversation - research doesn't have definite answers. "be wary of the way generative AI tools confidently state answers and flatten nuance into a single final answer rather than an idea or area to be explored and discussed"
    - Research as Inquiry - "prompt engineering as a mini version of the research cycle", "Research is iterative and depends upon asking increasingly complex or new questions whose answers in turn develop additional questions or lines of inquiry in any field."

Engaging deeply with generative AI often subverts the traditional process of strategic exploration. Instead of navigating a complex landscape of diverse sources, evaluating their origins, and synthesizing varying perspectives, the user is immediately handed a pre-synthesized, authoritative-sounding answer. This algorithmic mediation can severely erode learner autonomy and short-circuit the critical thinking process, as the AI effectively performs the cognitive labor of sifting and synthesis on the user's behalf. To preserve intellectual rigor, librarians and educators are actively adapting established evaluation heuristics to address the specific vulnerabilities of LLM outputs.


SIFT Method Mike Caulfield
https://open.umn.edu/opentextbooks/textbooks/454
Stop: Before accepting an AI's output, users must consciously pause. This step is designed to interrupt the affective or cognitive ease of receiving a fast, highly confident answer. It requires the user to recognize their own knowledge gaps and critically reflect on the inherent limitations—such as hallucination risks and automation bias—of the specific platform they are utilizing.

Investigate the Source: In the context of AI, investigating the source means understanding the architecture of the model itself. Is the output generated by a public LLM lacking real-time internet access, or a specialized RAG tool linked to a verified scholarly database? Understanding the provenance of the AI's training data, its temporal knowledge cutoffs, and its algorithmic constraints is a critical prerequisite to trusting its output.

Find Better Coverage (Lateral Reading): Instead of continuing a chat thread to ask the AI to verify its own correctness—a practice that often yields circular, hallucinated confirmations—the researcher must practice lateral reading. This involves opening a new tab and verifying the AI's claims using traditional, trusted academic databases like PubMed, JSTOR, or Web of Science.

Trace Claims, Quotes, and Media to the Original Context: This move constitutes the most robust defense against AI hallucination. If an AI provides a citation or a direct quote, the researcher must independently locate the DOI, access the original full-text article, and confirm that the paper actually supports the claim the AI has generated. Tools like Scite are invaluable during this phase, allowing users to trace how that specific claim has been received, replicated, or refuted by the broader scientific community over time.

https://aace.org/review/caulfield-ai/

STOP. Ask yourself whether you recognize the website or source, and what the reputations of both the claim and the source are.

INVESTIGATE. Not sure about that reputation? Learn about the source before you let the information sink in. Knowing its expertise and agenda is crucial to interpreting what it says.

FIND. Still concerned? Look for the best available source on this topic—or, just as importantly, scan multiple sources to see where expert consensus lies.

TRACE. Much of what we find online has been stripped of context. Trace the claim, quote, or media back to its origin so you can see it in its original context and judge whether the version you saw was accurate or misleading.


CRAAP Test

- Currency: Is the AI relying on outdated training data, or failing to retrieve the most recent empirical studies due to knowledge cutoffs?
- Authority: An AI system cannot be considered an author, nor does it hold intrinsic academic authority. The authority must reside entirely in the verifiable, human-authored peer-reviewed papers it cites.
- Accuracy: Evaluated continuously through the SIFT tracing method, ensuring the AI's summarization aligns with the original author's intent.
- Purpose: Understanding the commercial, design, or algorithmic biases of the AI tool itself. Commercial LLMs are often fine-tuned for user engagement and helpfulness, sometimes prioritizing the delivery of a plausible-sounding answer over admitting ignorance or ambiguity.