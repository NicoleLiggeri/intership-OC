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

Next, I looked for a rough alignment with the **Library of Congress classification**, but the results were unsatisfactory. The lack of subcategories makes it difficult to compartmentalize the areas effectively.

I updated on github the Excel file I’ve been working on so far.

