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

# Day 4 and 5 (6/4/2024 - 7/4/2024) - 10h
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

## Day 11 (9/12/2024) - 5h
I aligned the Nature Index journals with the Library of Congress Classification (LoCC). The Nature Index organizes journals into approximately 80 categories, and article-level topics are decided using an AI system that factors in parameters like metadata and citations. This AI-driven classification is open source for 12 months but doesn’t allow downloads, limiting long-term or detailed topic-level use.

Many Nature Index categories correspond directly to LoCC fields, but some interdisciplinary areas, like nanoscience, required more nuanced alignment. I annotated overlaps and interdisciplinary links where needed. While the LoCC structure worked for traditional fields, it struggled with emerging hybrid categories.
