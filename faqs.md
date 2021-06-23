---
title: Extra Questions
permalink: /faqs
---

The [Express version 2 of these materials](https://au-research.github.io/FAIR-data-101-training/fair-101-v2), presented a Q&A webinar for each of the Guiding principles.

* [FAIR Data 101 Express: Findable Q&A](https://www.youtube.com/watch?v=6KAR4jJVK8I)
* [FAIR Data 101 Express: Accessible Q&A](https://www.youtube.com/watch?v=0tR-K7DKD3Q)
* [FAIR Data 101 Express: Interoperable Q&A](https://www.youtube.com/watch?v=ZeK9z-gLH5Y)
* [FAIR Data 101 Express: Reusable Q&A](https://www.youtube.com/watch?v=55z2WcR1tgk)

If there were questions answered during the webinar, you can find them here. 

Please note that the Slack referenced in the webinars was only intended to be used among participants who registered for that version of the course. 

#### Questions we didn’t get to in the Live Q&A session

### Findable 

**How do you rank the Google datasets tool for Australian researchers to locate datasets?**

Answer: We’ve been working on our integrations to ensure that Australian research data is more easily discoverable through Google dataset search. More detail on that to come in interoperability. 

**RE: DOIs for grey literature pubs - there were 6 "core" fields that were displayed, but the DOI minting portal does allow for additional metadata, such as author affiliations, author identifier, etc. To what extent are external DOI minters encouraged to populate these additional fields?**

Answer: This depends on the external minter and their needs - factors like institutional policy can influence the importance of gathering additional fields for example. 

**That metadata visualisation was done 10 years ago. Would you say it has changed a lot?**

Answer: No, probably not a lot. There are still an awful lot of metadata standards out there. A few might have become deprecated, but others have emerged as new systems are developed.

**Slightly unrelated question - as academic organisations build their business development offices and aim for commercialisation deals from their research - do you find that there is less open data made available?**

Answer: Commercialisation offices have been around for a while at many universities. Their considerations around sharing research findings have been part of the FAIR and Open Data discussion for several years. Where data is a critical element in developing a patent it makes sense to not make that data openly available. However in many instances there are no such clear plans. Also publishers and funders are increasingly requesting the underlying data to be made available alongside a journal article or as an outcome of the research funding.

**Can you expand on how Research Data Australia obtains references to data? Is it just if it is held by an Australian institution? E.g. if an Australian lab/Institute publishes data in a European repository it won't be included in Research Data Australia?**

Answer: That depends on the metadata that the lab/Institute makes available for harvest by RDA, using the OAI-PMH. We’ll get more into this next week in Accessible and Interoperable.  

**Does [using a DOI] promote browsing and discovery through serendipity?**

Answer: It can do yes. Being able to click through to a research object via a DOI does make it easier to browse through works.

**Many universities have developed data stores (eg UQ RDM, Uni Sydney RDS etc). Are those stores connected to RDA automatically to be findable? Does Google Dataset Search index them too?**

Answer: Indeed they are. Nearly all university data repositories feed through the Research Data Australia. Research Data Australia automatically feeds this information through to Google Dataset search, so all data sets discoverable through Research Data Australia are also automatically findable through Google Dataset Search.

**Is there a difference between findability and discoverability? thanks.**

Answer: These are often different sides of the same coin. Findability responds to the quest of the person (or service) who is looking for the data, ie, it has a focus on the user. Discoverability refers to what the service provider (eg repository) does to enable their collection to be searchable.

**Would that lead to Institutions having ORCiDs? (can institutions currently have ORCiDs?)**

Answer: There is a different PID for organisation - [RoR](https://ror.org/scope/).  

**How early in the research project lifecycle would you obtain a DOI for the research data?**

Answer: There is no firm answer on this as cases and workflows vary to much. However, as a general rule, when the data is in a cleaned and finalised state and  entered into a repository/database that would be an ideal time. 
For a dataset that is still being actively used for the research a Handle may be more appropriate. 

**That is the bottle neck of Open Science: the reward system. To give credit to GOOD DATA SHARED and cited. But we do not need the same mistake with the data that we have done with publications. Not only measuring "data citation" but data sharing, etc.**

Answer: Yes, changing what we value and how we encourage that cultural change is a long game. 

### Accessible 

**Clearly the specifics (e.g. the Consent) aren't going to be unified if some mediation is involved. Is there any international move on the forms of access - others probably face the same questions.**

Answer: In terms of international efforts towards categories of access, you could take a look at the [UK Data Service’s three-tiered access model](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/access-control/three-tiers-of-access.aspx).

**I guess I'm looking at pass-through data. I want to share already publicly available information more readily (say [NCBI Refseq](https://www.ncbi.nlm.nih.gov/refseq/)), I feel like it is less complex but not sure what I'll get caught out by.**

Answer: This is an interesting question - pass-through data sounds like you’re talking about working data, or using a repository with analytic/ interrogative functions. Recognising the range of contributions and submissions to NCBI’s databases, NCBI in fact don’t license the content. We’ll dig into licensing a little more in the final week. This article has some useful discussion about decisions you need to make when sharing data similar to what you might find in NCBI’s RefSeq:[“Ten quick tips for sharing open genomic data”](https://doi.org/10.1371/journal.pcbi.1006472) 

**Do we have examples for managing data access, where an inhomogenous mix of access rules applies to a single data product? An example is sharing calibration data across independent measurement or observation campaigns to maximize the efficiency of an expensive facility. Here access rules between campaigns can differ, whereas some fraction of the data package/product is commensal.**

Answer: You could look at [AURIN](https://aurin.org.au/), which combines urban infrastructure data across a range of private and public sources, and mediates access for researchers, government and industry users. 

**What if researchers in my institution are reluctant to share data?**

Answer: Researchers can be reluctant to share data if there is no perceived immediate benefit. Often a salient benefit of preparing research data to share is that it’s easier for the researcher to find it and reuse it themselves in the future. Although many research funders and journal publishers now require a data availability statement, there may be specific reasons why some research disciplines do not encourage data sharing. It might be worth having a longer conversation about what your researchers’ needs are in relation to managing active data, and starting from there.

### Interoperable 

**(regarding linked data:) Would relational database be used to reflect relationships between objects?**

Answer: Linked data does not generally used relationship databases (such as SQL). Relational databases are limited in that relationships can only be defined with records in the same database. One of the strengths of linked (open) data is that any publicly-available dataset can be linked to.

**Do some of the platforms e.g. FigShare 'build in' elements of interoperability by default? If our dataset is hosted there, is it meeting FAIR standards?**

Answer: The various data repository platforms all build in some elements of the FAIR principles, but still put some of the onus on the data depositor. For example, most data repositories let you add keywords to your metadata record, but they do not necessarily require you to add keywords from a vocabulary that follows FAIR principles. It would be up to you to do that.

### Reusable 

(All questions were answered during the live Q&A session).
