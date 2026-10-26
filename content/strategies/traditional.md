---
section: Strategies
nav_order: 3
title: Traditional Search
topics: 
---

Searching for library resources is not the same as using Google!
Natural language phases do not typically provide good results. 
The quality of your literature review depends on careful consideration of your subject keywords.

- Keyword selection and concept mapping
- Booleans operators to expand, narrow, and refine your search terms
- Citation chaining to explore who is cited in your research area

For example, if your research question is "Does fracking cause water pollution?" 

| fracking | water | pollution |
| --- | --- | --- |
| hydraulic fracturing | underground water | contamination |
| drilling for natural gas | aquifers | toxins |
| natural gas wells | wells | carcinogens |
| directional drilling | domestic water supply | flammable water |
{:.table .table-bordered}

Using the search string "fracking water pollution" will interpreted as the Boolean `fracking AND water AND pollution`.
We can combine the synonyms brainstormed above to create a more advanced Boolean search:

`(fracking OR "hydraulic fracturing") AND (water OR aquifer* OR wells) AND (pollut* OR contaminat* OR carcinogen*)`

{% capture activity %}
## Develop Keywords 

- Write down your research topic or question.
    - Start from a potential group project topic: Palouse Groundwater Management, Campus Clean Energy Technologies, STEM Literacy and Learning Experiences, Sustainable Campus Events and Operations.
- Underline the key terms.
- Starting from your known topics, write down some:
    - Broader concepts
    - Narrower concepts
    - Related concepts
    - Synonyms

## Boolean Searching

- Go to the database [ProQuest SciTech Premium](https://uidaho.idm.oclc.org/login?url=https://search.proquest.com/scitechpremium?accountid=14551).
- Test your keywords:
    - Experiment with different uses of AND, OR, and NOT
    - Try `*` wildcards to allow multiple word endings
- How do the number of results change? 
- How do the type of results change? 
- Do results bring up new related terms and keywords?

## Citation Chaining

Good scholarship builds on other good scholarship!
Citations are an essential part of scholarly literature. 
They are also incredibly useful for starting your research.

If you know one good article in your topic area, you can explore the works it cites, and the newer articles that cite it. 
Scholarship is a network!

- Go to [Web of Science](https://uidaho.idm.oclc.org/login?url=http://webofknowledge.com/UA).
- Select "title" and search for `Review of district heating and cooling systems for a sustainable future`
- View the article record:
    - Explore works that cite the article
    - Explore works that the article cited
    - Explore keyword topics
    - Do we have access to the article? 
{% endcapture %}
{% include card.html text=activity header="Practice Search Strategies" %}
