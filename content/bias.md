---
#section: Strategies
#nav: Bias
nav_order: 3
title: Cognitive Biases
topics: 
---

Research is always impacted by our cognitive biases--we need to be aware of them to minimize how they distort our research and ability to evaluate sources. 

This is particularly true with AI assistants, as their highly confident and polished responses are easy to accept uncritically. 
AI won't flag its own hallucinations, won't show you dissenting viewpoints unless prompted, and presents uncertain claims with fluent confidence.

Below are some common cognitive biases that distort how researchers interact with and evaluate generative AI outputs:

## Confirmation Bias

People tend to seek out and favor information that confirms existing beliefs or hypotheses, which can be amplified by the conversational and agreeable nature of generative AI.
In AI research you might encounter this bias:

- Query Formulation: we often naturally phrase prompts in leading ways (e.g., *"Why does X intervention cause Y outcome?"*), prompting the model to structure an answer that assumes the premise is already true. If you ask "why does X work?" you'll get reasons X works; if you frame the question skeptically, you'll often get skepticism back--AI echo effects. This creates a subtle illusion of having "researched" something when you've really just had your prior views restated persuasively.
- Agreeableness: LLMs are engineered to be helpful and conversational. Instead of challenging a user's faulty assumption or surfacing scientific nuance, the model often tailors its response to validate the user's framing, generating plausible-sounding rationales that obscure deeper research. This can inadvertently reinforce a hypothesis by surfacing supportive material first or by reframing the question toward a desired answer, narrowing the literature scan and weakening the study’s validity.

## Automation Bias

This is the tendency to over-trust output from automated systems, treating machine-generated answers as more objective or reliable than human judgment--even when we'd challenge the same claim from a person. 

With AI tools, automation bias shows up as accepting a generated answer at face value without checking sources or noticing when the model has hallucinated a citation, statistic, or fact. 
We tend to accept AI answers because the tool articulated it with authoritative, academic phrasing.
After having success with some outputs, we grow to assume all outputs will be accurate without questioning. 

## Fluency Illusion

Well-written, coherent text feels true--and AI produces smooth text delivered in a conversational, agreeable, and authoritative manner. This bias makes readers conflate readability with credibility. A confidently cited but fabricated source *feels* more trustworthy than a clunky but legitimate one.

## Anchoring Bias

The tendency to disproportionately anchor subsequent judgment on the first piece of information encountered. 
If this is your first time exploring the topic, a authoritative sounding response from an AI tool can become your base line truth, sounding cohesive and plausible, which can cloud future understanding of the topic and constrain your questions.

Similarly, when AI summarises complex material, the summary's clarity can create a false sense of mastery: you feel you understand a topic deeply when you've only absorbed a compressed or basic version of it. 

---------------

## Methods To Avoid Biases

Navigating and evaluating AI outputs is similar to other information literacy approaches you have learned about to support research.
Rather than just evaluating the credibility of a primary source, you are now also evaluating the AI's interpretation of the sources.

Approaches:

- Restate your query using neutral and opposing-frame language.
- Ask the tool to present opposing views and counter-arguments.
- Treat AI output as a lead, not a conclusion.
- Verify claims against the primary sources.
- Actively seek counter evidence to key claims.
- Lateral reading.
- Use the SIFT method.

### Lateral Reading

Lateral reading is a technique that involves reviewing additional sources of information about an author, publication, claim, or organization. If you think of vertical reading as moving up and down a webpage to read its contents, then lateral reading involves opening more tabs to find more sources about the contents of the original page. You can look up websites, newspaper titles, authors, publishers, etc., in Google and Wikipedia to see what other voices say about the source you are investigating. 

Don't take a single source's word on its own! Instead, read laterally, and find more information to confirm or deny claims.

### SIFT Method

Developed by [Mike Caulfield](https://open.umn.edu/opentextbooks/textbooks/454) as a fact checking approach:

- Stop: Before accepting an AI's output, users must consciously pause. This step is designed to interrupt the affective or cognitive ease of receiving a fast, highly confident answer. It requires the user to recognize their own knowledge gaps and critically reflect on the inherent limitations—such as hallucination risks and automation bias—of the specific platform they are utilizing.
- Investigate the Source: In the context of AI, investigating the source means understanding the architecture of the model itself. Is the output generated by a public LLM lacking real-time internet access, or a specialized RAG tool linked to a verified scholarly database? Understanding the provenance of the AI's training data, its temporal knowledge cutoffs, and its algorithmic constraints is a critical prerequisite to trusting its output.
- Find Better Coverage (Lateral Reading): Instead of continuing a chat thread to ask the AI to verify its own correctness—a practice that often yields circular, hallucinated confirmations—the researcher must practice lateral reading. This involves opening a new tab and verifying the AI's claims using traditional, trusted academic databases like PubMed, JSTOR, or Web of Science.
- Trace Claims, Quotes, and Media to the Original Context: This move constitutes the most robust defense against AI hallucination. If an AI provides a citation or a direct quote, the researcher must independently locate the DOI, access the original full-text article, and confirm that the paper actually supports the claim the AI has generated. Tools like Scite are invaluable during this phase, allowing users to trace how that specific claim has been received, replicated, or refuted by the broader scientific community over time.
