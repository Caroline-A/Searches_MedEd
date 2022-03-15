# Preliminary search in Cristin via Tableau DUCT

# Journal search
Used 24 central journals in Medical Education from  Maggio, LA, Ninkov, A, Frank, JR, Costello, JA, Artino, AR. Delineating the field of medical education: Bibliometric research approach(es). Med Educ. 2022; 56( 4): 387- 394. https://doi.org/10.1111/medu.14677 

Searched for all publications in these journals within Cristin timeframe (2011-2020). Searched with filters:
* NVI subset

#### Issue using journals
Where is medical education research? Comment from  Kyungjoon Lee, Julia S. Whelan, Nancy H. Tannery, Steven L. Kanter & Antoinette S. Peters (2013) 50 years of publication in the field of medical education, Medical Teacher, 35:7, 591-598, https://doi.org/10.3109/0142159X.2013.786168 
> However, importantly, more than 80% of all ME articles were not published in ME journals. The 13 ME journals that existed, even briefly, during the 50 year period published only 18% of all ME articles (n = 14 753).

#### Search

```
IF CONTAINS(LOWER([journal]),	"academic medicine"	)
OR CONTAINS(LOWER([journal]),	"advances in health sciences education"	)
OR CONTAINS(LOWER([journal]),	"advances in medical education and practice"	)
OR CONTAINS(LOWER([journal]),	"african journal of health professions education"	)
OR CONTAINS(LOWER([journal]),	"anatomical sciences education"	)
OR CONTAINS(LOWER([journal]),	"bmc medical education"	)
OR CONTAINS(LOWER([journal]),	"bmj simulation & technology enhanced learning"	)
OR CONTAINS(LOWER([journal]),	"canadian medical education journal"	)
OR CONTAINS(LOWER([journal]),	"clinical teacher"	)
OR CONTAINS(LOWER([journal]),	"education for health"	)
OR CONTAINS(LOWER([journal]),	"focus on health professional education"	)
OR CONTAINS(LOWER([journal]),	"gms journal for medical education"	)
OR CONTAINS(LOWER([journal]),	"international journal of medical education"	)
OR CONTAINS(LOWER([journal]),	"journal of continuing education in the health professions"	)
OR CONTAINS(LOWER([journal]),	"journal of educational evaluation for health professions"	)
OR CONTAINS(LOWER([journal]),	"journal of graduate medical education"	)
OR CONTAINS(LOWER([journal]),	"journal of medical education and curricular development"	)
OR CONTAINS(LOWER([journal]),	"journal of surgical education"	)
OR CONTAINS(LOWER([journal]),	"medical education"	)
OR CONTAINS(LOWER([journal]),	"medical education online"	)
OR CONTAINS(LOWER([journal]),	"medical teacher"	)
OR CONTAINS(LOWER([journal]),	"perspectives on medical education"	)
OR CONTAINS(LOWER([journal]),	"simulation in healthcare-journal of the society for simulation in healthcare"	)
OR CONTAINS(LOWER([journal]),	"teaching and learning in medicine"	)
THEN "MedEd"
ELSE "non"
END
```