# Intership OpenCitations - Nicole Liggeri

## Day 1 (5/12/2023) - 5h
- Introductory meeting to establish the main goals of the internship.
- Completed the reading of suggested articles for a general understanding of the structure of OpenCitations.
- General overview of Scimago, ERIH-PLUS, DBLP, PubMed, DOAJ.

## Day 2 (6/12/2023) - 3h
- I have created a table to update the characteristics of various journal ranks (quality, license, list of primary classification, secondary classification, etc.).
- I started by analyzing Scimago, but then I moved on to ERIH-PLUS (excellent quality, cc by, etc.).
- ERIH-PLUS connects to a long list of other journal ranks (about fifteen - VABB-SHW, SciELO ecc.) and I have superficially checked some of them. I have added all of them to the table.

## Day 3 (18/1/2024) - 6h
- I have updated the table with information related to Scimago, ERIH-PLUS, DBLP, PubMed, DOAJ. Except for Scimago, the other lists are published under CC BY or CC0.
- I copied and saved the list of ERIH-Plus.

## Day 4 and 5 (6/4/2024 - 7/4/2024) - 10h
I have delved into the topic of scientific literature classification to better define the methodology to follow in the subsequent weeks.

Now I know that there are several ways to perform journal classification:

- One can rely on content-based classifications such as the one employed in the Library of Congress (Bensman, 2007) or disciplinary databases (Eykens, Guns, & Engels, 2019). Using these classifications, the assumption is that a manual inquiry of the content of a publication (e.g., title, abstract, full-text) is the best approach to identify relevant disciplinary categories.
- Another approach is to employ a citations-based classification approach (e.g., based on direct citations or bibliographic coupling) to identify clusters of publications of distinct academic disciplines or specialties.
- Thirdly, one can use text-based algorithmic approaches or a hybrid text and citation-based approach.
- Finally, it is possible to use a more basic and pragmatic approach and rely on journal classifications. However, it's noted that journal-based methods tend to be less accurate compared to manual or automated methods applied at the article level.

Other fun facts: 

> "We argue that, just like any other classifications, disciplinary classifications are social achievements resulting from local and context-specific considerations and negotiations. [...] In the recent decade, a number of new data sources have emerged (e.g., Dimensions, Microsoft Academic, Crossref, and (earlier) Google Scholar). However, studies investigating their coverage indicate that coverage is still low for SSH, especially for publications in languages other than English. Thus, at the moment, national databases remain the data sources that offer the most comprehensive coverage for research output in SSH." - Linda Sīle. Tracing the context in disciplinary classifications

> "Moreover, there are apparently non-systematic differences between fields in the extent to which journal contents match their Scopus classifications, so there is no general rule about the types of fields in which journal classifications are reliable." - Thelwall, Mike & Pinfield, Stephen. (2023). Are Scopus journal field classifications ever misleading?

I have found some classification systems that seem to be good starting points for further investigation. 

<details>
<summary>List of articles read</summary>


- Kulczycki, E., Engels, T.C.E., Pölönen, J. et al. Publication patterns in the social sciences and humanities: evidence from eight European countries. Scientometrics 116, 463–486 (2018). https://doi.org/10.1007/s11192-018-2711-0
- Linda Sīle, Raf Guns, Frédéric Vandermoere, Gunnar Sivertsen, Tim C. E. Engels; Tracing the context in disciplinary classifications: A bibliometric pairwise comparison of five classifications of journals in the social sciences and humanities. Quantitative Science Studies 2021; 2 (1): 65–88. doi: https://doi.org/10.1162/qss_a_00110
- Lavik, Gry & Sivertsen, Gunnar. (2017). Erih Plus – Making the Ssh Visible, Searchable and Available. Procedia Computer Science. 106. 10.1016/j.procs.2017.03.035.
- Daraio, C., Glänzel, W. Grand challenges in data integration—state of the art and future perspectives: an introduction. Scientometrics 108, 391–400 (2016). https://doi.org/10.1007/s11192-016-1914-5
- Thelwall, Mike, and Stephen Pinfield. "Are Scopus journal field classifications ever misleading?." arXiv preprint arXiv:2307.15449 (2023).
- Börner K, Klavans R, Patek M, Zoss AM, Biberstine JR, Light RP, et al. (2012) Design and Update of a Classification System: The UCSD Map of Science. PLoS ONE 7(7): e39464. https://doi.org/10.1371/journal.pone.0039464
- Engels, Tim & Istenic Starcic, Andreja & Kulczycki, Emanuel & Pölönen, Janne & Sivertsen, Gunnar. (2018). Are book publications disappearing from scholarly communication in the social sciences and humanities?. Aslib Journal of Information Management. 70. 10.1108/AJIM-05-2018-0127. 
- Klavans, Richard & Boyack, Kevin. (2007). Is there a convergent structure of science? A comparison of maps using the ISI and Scopus databases. Proceedings of ISSI 2007. 
- Boyack, Kevin & Klavans, Richard & Borner, Katy. (2005). Mapping the Backbone of Science. Scientometrics. 64. 351-374. 10.1007/s11192-005-0255-6. 
- Boyack, Kevin. (2009). Using detailed maps of science to identify potential collaborations. Scientometrics. 79. 27-44. 10.1007/s11192-009-0402-6. 
- Klavans, Richard & Boyack, Kevin. (2006). Identifying a better measure of relatedness for mapping science. Journal of the American Society for Information Science and Technology. 57. 251-263. 10.1002/asi.20274. 





</details>

## Day 6 - 7 (16 - 17/12/2024) - 10h

Yesterday, I picked up the thread of my project again and downloaded the categories from the Library of Congress to finally work on the alignment. The primary categories total **21**, with a significant number of first- and second-level subclasses. The subclasses are too numerous to manage in a single Excel file, so after several attempts, I decided to handle the potential alignment of subclasses separately.

I decided to begin the alignment with **ERIH-PLUS**. I changed my approach several times but eventually settled on organizing a workflow based on the following premises:

1. My goal is to map the categories of ERIH-PLUS (22 categories with around 170 subcategories) to those of the Library of Congress (LOC).  
   
2. To establish a convergence, only two scenarios can occur:
    - The ERIH-PLUS category covers a **smaller section** of the same area of competence compared to the LOC category, such that `A ⊆ A'`.
    - The two categories **coincide exactly**, such that `A = A'`.

3. **Partially Overlapping Categories**:  
   If the two categories share only some areas of interest, it’s useful to study the ERIH-PLUS subcategories separately to align them with the base categories of LOC that fits best (`A ∩ A'`).

4. **Empirical Test**:  
   In cases of difficulty interpreting the categories, an empirical test is always valid: examine how the same journal item or article is cataloged in the two systems can help me.

Thus, moving forward with the workflow:

- I considered each **ERIH-PLUS class**, selecting the closest match in LOC.  
- I evaluated the **overlap** between the two classes, recording all compatible categories and subcategories.  
- In case of uncertainty, I planned to check how different journals were recorded in both databases — *or so I thought I would...*

### Results and Observations

I then produced a new file titled "LOC Alignment," which lists the 21 Library of Congress categories in the first column and records all ERIH-PLUS convergences (both classes and subclasses) in the second column. I enriched the ERIH-PLUS sheet by including the LOC subclasses that helped me make more precise matches. I used different colors to distinguish between included and non-included categories. 

At this point, I managed to cover about **half of the catalog**.  
An interesting case was the ERIH-PLUS category “History,” which, despite being fundamental, could not fit into any of the three LOC categories created for history. This was because it exceeded the scope of both “History of Americans” and “World History and History of Europe, Asia, Africa, Australia, New Zealand, etc.”


For all problematic categories, I planned to verify the databases. By directly using the links in the ERIH-PLUS category list—which lead to filtered database queries—I found only academic papers, even for various categories. None of the tests I conducted found matches in the LOC database. At this point, I decided to download the list of journals approved by ERIH-PLUS, which is easily available on their website. The journals are recorded with their titles (both international and local), ISSN, and ERIH-PLUS category.

It was here that **I discovered that the categories listed in the CSV file do not correspond to those I had been working on for hours**.  

Did I waste hours of work?
It’s more likely that there are different classifications depending on whether one is dealing with an article or a journal.  

There will be time tomorrow to explore this further.


## Day 8 (18/12/2024) - 4h

It turns out that yesterday’s work cannot be used. What I worked on was not the official ERIH-PLUS list but the ERIH-PLUS list provided by Dimensions.

> Classification systems in ERIH PLUS by Dimensions are automated emulations of standard classification systems used around the world, based on machine learning guided by topic experts. Thus, these provide an accurate representation of the classifications, labelling all fitting documents in ERIH PLUS by Dimensions automatically. Categories can be used in conjunction with keyword and abstract searches, or other filters, making searches through ERIH PLUS by Dimensions extremely simple and effective.

> You acknowledge that Dimensions is protected by copyright and other proprietary rights, which we and our licensors will retain. You will abide by all relevant copyright notices, usage restrictions and other additional licensing terms, including those on the acknowledgements page, and agree that any unauthorized use will result in the automatic termination of any rights granted to you. 

So, what are the real ERIH-PLUS categories? By digging through the official website, there appears to be no formal classification. However, one can infer the categories from the **approved journals list** published on the site. This results in **30 categories** without any subcategories.

These categories can be aligned - again, using the approved journal list - with another classification system: the **OECD-Frascati** (DOI: [10.1787/9789264239012-en](http://dx.doi.org/10.1787/9789264239012-en))(see page 59). Interestingly, I found an alignment between this schema and the **Web of Science** provided by InCites ([link to source](https://incites.zendesk.com/hc/en-gb/articles/22516984338321-OECD-Category-Schema#h_01HPJA60JPGFFFZAD6EAZGWB3B)). There are other alignments available between different schemas and the Web of Science.

Next, I looked for a rough alignment with the **Library of Congress classification**(LoCC), but the results were unsatisfactory. The lack of subcategories makes it difficult to compartmentalize the areas effectively.

I updated on github the Excel file I’ve been working on so far.


## Day 9-10 (26-27/12/2024) - 8h

Today, I worked a bit slowly on PubMed before deciding to change strategy. PubMed, being an aggregator of specialized articles, has a much finer granularity in scientific fields compared to LoCC. Moreover, finding matches for journals in PubMed with the Library of Congress classification is less straightforward than I anticipated. I therefore decided to temporarily set aside this alignment to explore other options.  

After a brief moment of satisfaction in remembering that **DOJA** uses the LoCC to catalog Open Access journals—and can thus be useful to observe how the classification is practically applied—I focused on the **ERA (Excellence in Research for Australia)** lists. ERA journal lists are designed to support Australia's national research evaluation framework, and I spent considerable time searching for the 2023 list, which appears to be used by Dimensions. Online, there’s a search engine that makes the list accessible ([link to source](https://online.library.uitm.edu.my/era/)), but there doesn’t seem to be any supporting file, nor could I find the resource directly on the Australian Government's website.  

For this reason, I gave up and instead found the 2018 version with approximately 25,000 journals (I’ve added the file to the repository). The list records journals and assigns one or more codes related to fields of study using the **ANZSRC 2008 FoR**. The new 2023 list likely uses ANZSRC 2020 FoR, which is why the website features a mapping between the two ANZSRC versions (ANZSRC 2020 was what I mistakenly thought was ERIH-PLUS in recent days, wasting time—though perhaps I’ve recovered it now?).  

Since I have the mapping between the 2008 and 2020 versions and have largely (though not entirely) aligned the 2020 version with the Library of Congress, I moved on to work on the **VABB-SHW**([link to source]([https://archive.org/details/norwegian_register_journals-2024-06-04](https://www.ecoom.be/en/data-collections/vabb-shw))) and carried out a reasoned alignment with LoCC (though validation is needed through comparisons between databases).
>Operated by the Centre for Research & Development Monitoring (Expertisecentrum Onderzoek en Ontwikkelingsmonitoring, ECOOM), the Flemish Academic Bibliography for the Social Sciences and Humanities (VABB-SHW) is a database of academic publications from the social sciences and humanities authored by researchers affiliated to Flemish universities. The full list of journals comprises both peer reviewed and not peer reviewed journals.
However, I later realized that the discipline is assigned at the article level (and not at the journal level).
>How are publications assigned to VABB-SHW disciplines? In the VABB-SHW we assign publications to disciplines on the basis of the affiliation(s) of the author(s). The research units to which authors belong, are assigned to one of 16 VABB-SHW disciplines or one of both general categories, allowing to assign each publication to at least one discipline or general category.

I then focused on the **Norwegian registers** ([link to source](https://kanalregister.hkdir.no/)), which are also included in Dimensions.  

>The Norwegian register, officially the "Norwegian Register for Scientific Journals, Series and Publishers," is jointly operated by the Norwegian Centre for Research Data (NSD) and the National Board of Scholarly Publishing (NPU). The list identifies which scientific publications are recognized in the weighted funding model and includes around 30,000 source titles. The Norwegian register divides journals and series meeting scientific quality criteria into Level 1 and Level 2, where Level 2 is superior to Level 1. These criteria include a valid ISSN, a scientific editorial board, and a peer-review process. Titles not meeting these criteria are classified as Level 0.

I found a downloadable version of the dataset ([link to source](https://archive.org/details/norwegian_register_journals-2024-06-04)), but there’s also a resource for simple and efficient searches ([link to source](https://npi.hkdir.no/fagfeltoversikt)).  

The Norwegian register has its own labels for defining scientific fields. Therefore, I carried out a more systematic and “empirical” alignment between the **DOJA** categories (and thus LoCC) and **ERA 2018** (and thus ANZSRC 2008 FoR). The register records which of its journals are present in DOJA, so my searches were much more effective.  

I am gradually making progress with this alignment. The progress has been saved in the file in the repository.

## Day 11 (30/12/2024) - 3h

Not much to report for today. I completed yesterday's work and searched through the datasets for matches to enable reliable alignment (Norwegian Register - DOJA - ERA 2018). It was fairly tedious work—I could have created a script to automate it and probably saved about an hour. Tomorrow, I'll take a more "big-picture" look to draw general conclusions and fill out the alignment sheet. 
I uploaded the updated file to the GitHub folder.

## Day 12 (9/01/2025) - 5h
I aligned the Nature Index journals with the Library of Congress Classification (LoCC). The Nature Index organizes journals into approximately 80 categories, and article-level topics are decided using an AI system that factors in parameters like metadata and citations. This AI-driven classification is open source for 12 months but doesn’t allow downloads, limiting long-term or detailed topic-level use.

Many Nature Index categories correspond directly to LoCC fields, but some interdisciplinary areas, like nanoscience, required more nuanced alignment. I annotated overlaps and interdisciplinary links where needed.

## Day 13 (10/01/2025) - 8h

I worked on clarifying the differences between PubMed, MEDLINE, and PubMed Central. I reaport it to have a written reminder:
- PubMed is a free resource that supports searching biomedical and life sciences literature, containing over 37 million references, including MEDLINE and other citations.
- MEDLINE is a journal citation database managed by the National Library of Medicine, indexing over 5,200 scholarly journals and including MeSH terms for standardized indexing.
- PubMed Central, launched in 2000, is a free archive for full-text biomedical and life sciences journal articles. If a citation appears in PubMed, it might include a link to PubMed Central for full-text access.  
The distinction between MEDLINE and PubMed seems tied to quality assurance and economic factors. Being listed in MEDLINE is a mark of quality. For journal categories, the NLM Catalog provides the most detailed indexing and classification information.  

I also explored other tools related to NLM. 
- The NLM Catalog provides bibliographic data for journals and other records, and includes indexing terms like MeSH and Broad Subject Terms.
- LocatorPlus is used for detailed records and circulation status but is less relevant for journal classification.
- NCBI databases focus specifically on journals and seem the most useful for my work. It is part of the NLM Catalog

Broad Subject Terms, used only for MEDLINE journals, are a subset of MeSH headings and provide limited but useful categorization. However, their coverage is far narrower than MeSH terms and since they are not used in PubMed I won't go deeper.

I moved on to align SciELO and DOAJ. SciELO is an electronic publishing platform with 1,654 journals from 15 countries in Latin America and the Caribbean. Its journal labels are broad and limited in number, especially for humanities disciplines, with only six total labels assigned to journals. Some journals in SciELO are not listed in DOAJ, ERIH-PLUS, or other platforms, making it an interesting resource despite its constraints.  

I began compiling additional journal lists for evaluation, including CORE, bioRxiv, and SSOAR. I’ve recorded these in an Excel file and plan to assess their relevance for classification and broader research in the coming days.

## Day 14 (11/01/2025) - 2h

Today, I continued my search for interesting databases. Many dead ends (many of the main databases are proprietary) – I documented everything in the Excel sheet, but there isn't much to report.  
Among the most interesting findings:  
- **ERIC**, a free database that provides access to educational research in the form of journal articles, research reports, conference papers, and more. The records are peer-reviewed and may include links to full-text articles. It primarily covers the field of Education.  
- **Eldis**, which until June 2024 was a database aggregating articles on Global Science. The creators made the data available under a CC-BY license, but it doesn't use a rigorous taxonomy (which, incidentally, can only be viewed within the database itself and is not detailed in the documentation). It uses around 300 keywords.  
- **Global Index Medicus**, by the World Health Organization. Interesting because it includes journals from non-Western regions. However, it uses MeSH for indexing articles and journals, which is the same system used by PubMed. This makes me think it feeds into PubMed, so it might not be worth spending too much time on it. However, an interesting lead emerged at the end of the search: I found a website linked to the WHO that seems to contain additional material. Worth exploring further.

## Day 15 (12/01/2025) - 5h
Today, I continued my research with rather few results, to be honest. An interesting public archive is ScienceOpen.com. However, although it includes metadata related to the scientific subject matter, these are article-level labels. To clean up the Excel file from failed attempts, I created a new summary sheet. I also gathered quantitative data to take stock of the situation. In practice, so far, I seem to have found only about 12 public databases with relevant metadata (including those like ScienceOpen or VABB-SHW that are annotated at the article level). If there were no overlaps or conflations – which is impossible – I would currently cover about 80,000 journals: still far from covering OC.

## Day 16 (13/01/2025) - 5h
I analyzed CORE, which, according to 2023 data, is the largest open-access article aggregator, sourcing from over 10,000 platforms. CORE appears to offer a filter for selecting articles based on categories; however, as of 2023, these labels do not seem reliable enough to support internal statistics within CORE. The last study on disciplines dates back to 2021 and was initiated by Microsoft Academic before it was discontinued ([DOI](https://doi.org/10.1038/s41597-023-02208-w)).

For this reason, I set CORE aside and analyzed NARCIS, which, according to the paper I read, should integrate into CORE. However, I later discovered that NARCIS was shut down in 2023, although its data can still be downloaded under a CC0 license. I looked at the files and found that NARCIS recorded the categories of its articles (in columns from `coverageX1` to `coverageX6`). Nonetheless, I decided to move on because I couldn’t find documentation explaining these categories, and I read that NARCIS was merged after its closure into the “Portal of Research Output from the Netherlands.”

I then consulted this other database and found that it integrates into OpenAIRE. Specifically, it offers classification labels at the article level (and only at the article level) through the use of an AI algorithm. The classification follows the Frascati guidelines published by the OECD. I attempted an alignment with the Library of Congress Classification, but the unsatisfactory results led me to try a cross-reference with DOAJ. Again, the results were poor—I couldn’t find compatible articles, even after applying a filter to display only articles published in the Netherlands.

I subsequently searched for other tools online and found the work of a researcher who developed a mapping between the OECD's revised Fields of Science and Technology (FoS) classification and the 2020 Australian and New Zealand Standard Research Classification (ANZSRC) ([link](https://figshare.com/articles/dataset/Mapping_OECD_s_Revised_Field_of_Science_and_Technology_FOS_Classification_to_Australian_and_New_Zealand_Standard_Research_Classification_ANZSRC_2020_Dimensions_/26491210?utm_source=chatgpt.com&file=48165955)).  

Tomorrow, I plan to review this mapping further to evaluate it more thoroughly.

## Day 17 (14/01/2025) - 5h

I decided to use the categories already developed for ERIH-PLUS to align with the OECD classification. Upon reviewing the CSV file with the complete list of its journals, I noticed that ERIH-PLUS saves them with both its internal categories and the OECD ones. While rechecking the file, I also discovered some oddities in the ERIH-PLUS database. For instance, for the "Journal of Gerontology," both series (A: Biological Sciences and Medical Sciences; B: Psychological Sciences and Social Sciences) are saved under the category "Psychology."

In any case, the OECD classification appears much less granular than ERIH-PLUS. For example, the category "Sociology" corresponds to "Gender Studies," "Environmental Studies," "Anthropology," and "Sociology." To finalize the alignment between OECD and LCC, I used OpenAIRE and compared it with data from DOAJ.

I tried to understand the purpose of the work I have been doing since OpenAIRE already seems to register categories and process them (using the OECD standard). Honestly, I couldn't find an answer. Perhaps not all articles have a subject assigned—but even in those cases, keywords are recorded, which OpenAIRE takes from the source databases. For instance, all articles registered in DOAJ as "Naval Science" don’t have a true OECD label, but in OpenAIRE, you can find “Naval Science” or the corresponding category in the registered keywords.

I also aligned the arXiv labels to LCC.

## Day 18 (15/01/2025) - 5h

I focused on searching for new databases. I began by distinguishing between ROAR and OpenROAR. The former is a repository database that allows for historical statistical analyses of repository growth, thus focusing on monitoring. The latter concentrates on providing an authoritative, accurate list of repositories with detailed information about policies, content types, and technologies used. 
The classification system in the first case relies on the Library of Congress system, while the second has a more generic classification system (I couldn’t find appropriate documentation on it).

I then obtained limited results with other databases, search engines, or tools that lack discipline-based classifications (e.g., Europe PMC).
- AGRICOLA: It includes a list of journals theoretically connected to agriculture but also covering topics such as economics and education. However, I imagine they can all be classified as agriculture or related fields.
- HAL is a very interesting French database. It operates under a CC-BY license, offers an API system, and even includes a triple store network. The category network is quite dense, and I plan to analyze it further tomorrow.
- LA Referenciais a Spanish database, also under a CC-BY license. For now, its server is down.
- African Journals Online: This database includes a list of journals under CC-BY. The categories are quite varied, but the number of journals is relatively small, in the range of a few hundred (each journal can have up to three categories).
- bioRxiv is a preprint database in the field of biology. I am unsure how useful it might be, but I assume it could be relevant.
- SSOAR (Social Science Open Access Repository): All metadata in this database is under a CC0 license, but it is already integrated into OpenAIRE. Tomorrow, I’ll check whether the categories are incorporated as keywords or as subject fields in OpenAIRE. 

## Day 19 (16/01/2025) - 5h
Contrary to expectations, OpenAIRE does not register the SSOAR categories either as keywords or as categories. I have therefore proceeded with the alignment to the LCC. Although it is a database focused on social sciences, it also includes other disciplines. I attempted to use DOAJ for the alignment, but since they operate on different levels (DOAJ on journals, SSOAR on articles — although it collects them within journals), the attempt was eventually abandoned. For this reason, at present (with a few exceptions), the alignment is only based on a comparison of the label names.

## Day 20 (17/01/2025) - 5h

Materials available on bioRxiv are also found on OpenCitations (see, for example, the preprint with DOI 10.1016/j.jinsphys.2014.05.025). However, it is important to note that some of these preprints, like that one, have subsequently become articles and are now indexed in PubMed (so maybe that's why they are in OC now). In PubMed, these articles include MeSH terms, which are significantly more comprehensive compared to the labels bioRxiv might offer. For example, the article titled “Amino acid and carbohydrate tradeoffs by honey bee nectar foragers and their implications for plant-pollinator interactions” has a unique label on bioRxiv, which corresponds to “Plant Biology.” In PubMed, the labels are much more detailed: “Amino Acids / physiology; Animals; Bees / physiology*; Dietary Carbohydrates; Flight, Animal; Food Preferences*; Homing Behavior; Nutritional Physiological Phenomena*; Plant Nectar / physiology*; Pollination; Sucrose.”

Some preprints are in the Pubmed database (registered as preprints) but not all preprints present on PubMed are also included in OpenCitations. For example, the preprint with DOI 10.1101/2024.06.05.597576 is indexed in PubMed as a preprint, with a clear mention of its origin from bioRxiv - still no mention in OC. On the other hand, not all biooRxiv preprints, even the older ones, are present in PubMed, however some are found in OpenCitations, such as the preprint with DOI 10.1101/017806. Therefore, it seems useful to collect this category of articles and preprints to better understand their distribution and indexing across bioRxiv, PubMed, and OpenCitations.

Today, I have worked on a possible alignment between bioRxiv and OpenCitations, hoping it might be helpful. 

I have once again tried to address the alignment between MeSH terms and LCC (using DOAJ) but without significant results.



## Day 21 (19/01/2025) - 5h

I got lost reading the OpenAlex documentation. OpenAlex offers CC-0 metadata. Among the metadata it makes available are those related to an article's topic, which are generated using NLP and DL techniques.  
Not all articles in OpenAlex have been assigned a topic, as a minimum amount of data is required. Specifically, each article must at least have a title and an abstract (or at least a minimum number of citations).  
<details>
   
OpenAlex was created to fill the void left by the discontinuation of Microsoft Academic Graph. OpenAlex has a system for classifying topics in research papers that leverages data from CWTS, a respected source for research classifications, which provides fine-grained, micro-level fields of study. They fine-tuned the multilingual BERT (mBERT) for this purpose. The system incorporates key features such as paper titles, abstracts, journal names, and citation networks. Particularly interesting was the use of "gold citations," a curated set of influential references that enrich predictions. This approach enhances the model’s ability to classify works even when textual data is limited or absent, a common challenge in multilingual and non-English contexts.  
Performance evaluations show the model’s strength in predicting topics under diverse conditions, with accuracy improving as the availability of input features increases. The system adapts well to real-world scenarios, where data may be incomplete, demonstrating resilience and versatility. However, challenges persist, particularly with sparsely populated clusters and ambiguities in topic assignments.  
   
</details>
   
I then focused on ScienceOpen.com to find documentation related to how they manage metadata for article categories. There’s no trace of documentation anywhere. I have to assume that authors themselves assign them.  

After that, I attempted to align MeSH with LCC again. A disaster, though somewhat more effective. This time I’m searching for all the medical subcategories under LCC (letter R) in DOAJ journals. Many of these subcategories are never used even once, but for those that are, I’m trying to collect as many different labels as possible. I’m especially focused on journals in DOAJ that fall exclusively under the specific category I’m studying, to avoid confusion among MeSH terms. For each LCC subject, I consider at least three journals and aim to record all their MeSH terms from PubMed.  

Concerns about this approach:  
- If an LCC category isn’t used in DOAJ, it doesn’t mean it’s ineffective for describing certain MeSH terms.  
- If a journal indexed under a specific LCC category has certain MeSH terms, it doesn’t mean those MeSH terms can only be used as equivalents of that category. For example, broad categories like Pathology: the MeSH term *Malaria* might consistently correspond to Pathology, but another term like *Microbiological Phenomena* could be used in one context to describe a journal in Pathology, and in another to describe a Biological category unrelated to the human body or diseases.  

Honestly, this seems like an exercise in futility. It’s about mapping a vast amount of data, and this should be done empirically with computational methods. A manually conducted project like this can never be rigorous.  

## Day 21 (24/01/2025) - 8h
Slow alignment Scimago - LCC: I am considering each subcategory of Scimago individually (around 300), as similar categories might be associated with different major categories in the LCC. Primarily, I am looking for literary correspondences between the categories of the two systems; only in complex cases I am considering comparison through Doaj.

## Day 22 (25/01/2025) - 7h
Almost completed alignment with SCImago. Uncertain about how to proceed; I’m not sure that the comparison with DOAJ is always effective. SCImago often includes many more categories, which creates noise. Moreover, there are direct correspondences between LCC and SCImago labels, but I don’t always find them reflected in the database comparison. Therefore, I prefer to record the direct correspondences but, during alignment, I imagine I’ll proceed by considering only the more general ones.

## Day 23 (28/01/2025) - 7h
I have completed the alignment with Scimago. I retrieved the mapping files for OECD-Frascati and WoS. I reviewed the SKOS-JSON files from the Library of Congress. I have proposed a new approach for MeSH terms; alternatively, I am considering using the broad subject terms, which are the discipline labels used exclusively for Medline journals.

## Day 24 (29/01/2025) - 7h
I’m still making no progress with MeSH. I decided to take a look at the [SKOS ontology](https://www.w3.org/TR/skos-reference/#intro). I checked all the most relevant properties. In particular, `skos:mappingRelated` is used to map similarities between different vocabularies. Its subproperties include `skos:relatedMatch`, `skos:closeMatch`, `skos:broadMatch`, and `skos:narrowMatch`.  
In my case, `skos:narrowMatch` could be particularly useful, as it links a more general term to a less general one.  
Perhaps it is more convenient to use `skos:relatedMatch`, `skos:closeMatch`, or `skos:exactMatch` in the case of a direct similarity between two terms. If the first one is too generic—ehm—and could be used, for example, to establish a link between "oviparous" and "egg," the second one seems more suitable because it establishes a more direct similarity.  
The advantage of using `skos:closeMatch` instead of `skos:exactMatch` is that the former is intransitive, making it safer to use in my case. Intransitive means that if A `skos:closeMatch` B and B `skos:closeMatch` C, nothing can be inferred about the relationship between A and C.  
Then, I found an [article](https://campus.dariah.eu/resource/posts/controlled-vocabularies-and-skos#skos-checklist) that is useful not only for providing an overview of SKOS but also for learning about common mistakes in vocabulary creation, as well as tools and libraries for building and validating results.  
Next step: converting or collecting the vocabularies I found into Turtle files.

## Day 25 (30/01/2025) - 6h
I organized the vocabularies I collected into CSV files. I converted the file into Turtle format using a Python script and used the SKOS vocabulary to define the hierarchies between terms.  
I gathered OECD, SCIelo, Scopus, ANZSRC, the Norwegian Register, and ERIH-Plus.  
I used `Skosify.py` and [SKOS Play] (https://skos-play.sparna.fr/skos-testing-tool/) to verify that the formatting was correct.

## Day 26 (31/01/2025) - 6h
I wanted to proceed with the actual alignment, starting from the most generic classes and then establishing `closeMatch` relationships between the subcategories. I began by searching everywhere for the complete vocabulary file from the Library of Congress in skos. I couldn't find it anywhere. So, I retrieved all the files and combined them together.  

This is where the problems started. First of all, when I ran the resulting file through the SKOS testing tool, it showed a series of issues, including “Disjoint Labels Violation,” “Missing Labels,” and “Overlapping Labels.” These problems cannot be attributed to the way I manipulated the data in Python but rather seem to originate from the original files.  
However, the most serious issue was something I only realized later: none of the vocabulary terms are defined as `skos:Concept`, not even the leaves of the hierarchy. A major oversight, I know. Instead, they are mostly structured as collections, or their type is simply not specified.  

This would still have been a valid approach if it weren’t for the fact that the SKOS ontology documentation clearly states that any relationship in SKOS is dependent on the conceptual nature of the entities involved:  

> “The domain and range of the SKOS semantic relation properties is `skos:Concept`. Therefore, if any of the SKOS semantic relation properties (e.g., `skos:narrower`) are used to link to or from a collection, the graph will *not* be consistent with the SKOS data model.”  

So, the choice is between **creating a new file**—one that is different from those provided by the Library of Congress—or violating the principles of the ontology. Furthermore, creating a new file doesn’t entirely bypass the issue, because the higher hierarchical levels would still be collections, meaning they **still** couldn’t have relationships.  
The best solution would probably be to create two separate files, depending on whether the alignment is done at the macro-category level or at the subcategory level.

## Day 27 (01/02/2025) - 7h
Today, I reconsidered my options with greater clarity. I hypothesized the possibility of using *skos:member* for alignment and adding to the collection’s members concepts that are outside that vocabulary. My strategy would have played entirely in the gray areas of legality—nothing about this improper use of the property is explicitly stated in the documentation.  

Then I decided that I am better than that and resigned myself to annotation at the second hierarchical level.  
The second level, despite not being a leaf level in the hierarchy, is not explicitly defined as a collection, so I was able to treat it as an *skos:Concept* and use the Mapping Properties.  

At this point, the problem is that, for the sake of simplification in the alignment, I often did not link categories to the second hierarchical level but to the first. To address this issue, I realized that in many cases, I could use the “General” category, which is included in the Collection a significant number of times. For all other cases, I decided that, in most instances, my judgment is sufficient to determine which subcategories are the closest match to the vocabulary.  

However, I still encountered some difficulties, such as the case of Musicology, which I wasn’t sure where to place, so I added it to all of Music’s subcategories. Or Linguistics and Literature, which I can no longer group together—I'm still deciding how to handle this case. I’m considering using *skos:broaderMatch*, but I haven’t yet decided whether it’s the right approach.  

I’ve more or less aligned the first half of the LCC Collections. In the meantime, doubts about the alignment have started to arise, so I’ll have to review everything before submitting it.  

Also, only halfway through did it occur to me that, instead of labels, I probably should have created numerical IDs for all vocabularies. Well, too late. I’ll ask if it’s necessary.

## Day 28 (02/02/2025) - 5h
Today, I completed the SKOS alignment and added WoS, which I had forgotten. I reconsidered the possibility of using `skos:narrowMatch` and  `skos:broaderMatch`. For example, "Philosophy, Ethics, and Religion" from the OECD will be excluded if I won't use `skos:broaderMatch`.

## Day 29 (03/02/2025) - 5h
I have double-checked all the alignments to confirm that I haven't missed anything relevant. I have decided that `skos:narrowMatch` is not useful in my case, and in fact, I'm not even sure anymore that I have chosen the right approach for the alignment. I have started aligning PubMed using the broad terms. The broad terms have much more limited coverage because they refer only to Medline; however, they are much more manageable in the alignment.
