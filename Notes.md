# Notes

## Analysis
* Consider decadal

#### Deduplication

Step 1: The CRISTIN results cannot be imported into EndNote. Therefore I did a deduplication in Tableau before any other work. I took the Web of Science results and joined this data to the CRISTIN data, by exact matching on the doi. This detected 161 duplicates between the CRISTIN and WoS sets, that were removed. I then did the same with PubMed, where there were 134 duplicates. Once both were removed, there remained 304 results from the CRISTIN set (of 488 originally). These were then exported to Excel, and added to Zotero using the doi-lookup function (for those with doi). The remaining references were added manually. 297 were added (7 were removed for being obvious conference proceedings) - these were then exported from Zotero, and added to EndNote along with the exports from PubMed, WoS and ProQuest.

Step 2: After all was in EndNote, I followed first steps of the procedure in Bramer, W. M., Giustini, D., de Jonge, G. B., Holland, L., & Bekhuis, T. (2016). De-duplication of database search results for systematic reviews in EndNote. Journal of the Medical Library Association : JMLA, 104(3), 240–243. https://doi.org/10.3163/1536-5050.104.3.014. Then used doi (together with manual checking). Due to the order of import, the order of preference for retention was WoS > PubMed > ProQuest > CRISTIN. 

I then ran "Find reference updates" on the final set, to find PubMed IDs for any records that did not have a WOS ID or PubMed ID in the Accession Number field. Other data was added for empty fields (e.g. Keywords) or overwritten in the case of ProQuest records (to reformat the DOI to a standard format, and get the PubMed accession number instead of ProQuest for later analysis). 

#### Import/Export to Rayyan
We can retain the WOSID/PMID throughout the screening process by 
1. Importing to EndNote - PMID and WOSID both end up correctly in the Accession number field. In Zotero they end up in different fields.
2. Deduplicating
3. Copying Accession number field contents over to the URL field, as well as PMCID. Could theoretically do this with the doi too.
4. Import into Rayyan via RefMan (Export, txt, Refman output style)
5. Export from Rayyan using EndNote again. DOI is lost, but the URL field is retained.  

## Example articles to test search against
Should be found
* Kristin Wigen, Are Holen & Øyvind Ellingsen (2003) Predicting academic success by group behaviour in PBL, Medical Teacher, 25:1, 32-37, DOI: 10.1080/0142159021000061396
* Gude, T., Hjortdahl, P., Anvik, T., Bærheim, A., Fasmer, O. B., Grimstad, H., ... & Vaglum, P. (2005). Does change from a traditional to a new medical curriculum reduce negative attitudes among students? A quasi-experimental study. Medical teacher, 27(8), 737-739.
* Smeby, S. S., Espeland, T., Berg, E. A. R., Samstad, E., Lillebo, B., & Slørdahl, T. S. (2021). Examining the educational impact of the mini-CEX: a randomised controlled study. BMC.

## Indexing in PubMed of central journals
The coverage comment below is from Maggio, L.A., Costello, J.A., Norton, C. et al. Knowledge syntheses in medical education: A bibliometric analysis. Perspect Med Educ 10, 79–87 (2021). https://doi.org/10.1007/s40037-020-00626-9
> "While all of these journals are indexed in PubMed, seven of them are not included in their entirety, namely: 
> Advances in Health Sciences Education, Canadian Medical Education Journal, Clinical Teacher, Medical Education Online, Medical Teacher, Teaching and Learning in Medicine, and The Journal of Continuing Education in the Health Professions. For example, Clinical Teacher first appeared in PubMed in 2010, but the journal started publishing articles in 2003.".

From below, I can see that 12 of them have the same start/index date. 9 have gaps (2 x 2 years, 3 x 6-7 years, 4 x 11+ years), 3 are not indexed. We will find any missing publications from 2011 and onwards in the Cristin search. Other publications before this may be missing.

#### Data I have checked from PubMed, start date and indexed from date:
* academic medicine, 1989, 1989
* advances in medical education and practice, 2010, 2010
* anatomical sciences education, 2007, 2008
* bmc medical education, 2001, 2001
* gms journal for medical education, 2016, 2016
* international journal of medical education, 2010, 2010
* journal of educational evaluation for health professions, 2006, 2006
* journal of graduate medical education, 2009, 2009
* journal of surgical education, 2007, 2007
* medical education, 1976, 1976
* perspectives on medical education, 2012, 2012
* simulation in healthcare-journal of the society for simulation in healthcare, 2006, 2006

--

* journal of medical education and curricular development, 2014, 2016 (not in MEDLINE)
* canadian medical education journal, 2010, 2012 (not in MEDLINE)
* advances in health sciences education, 1996, 2001
* clinical teacher, 2004, 2010
* education for health, 1996, 2003
* teaching and learning in medicine, 1989, 2000
* journal of continuing education in the health professions, 1988, 2000
* medical education online, 1996, 2008
* medical teacher, 1979, 2002

--

* african journal of health professions education, 2009, not indexed in MEDLINE, only selected citations from PMC
* bmj simulation & technology enhanced learning, 2015, not indexed in MEDLINE, only selected citations in PubMed
* focus on health professional education, 1999, not indexed
