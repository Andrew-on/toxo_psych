# toxo_psych
## Summary

The entire data analysis consists of two parts: the first part involves conducting basic two-sample Mendelian Randomization using the TwoSampleMR R package, and the second part involves performing a meta-analysis using the metafor R package to estimate the overall causal effects of Toxoplasma gondii infection on various psychiatric diseases. 

## Data source

All summary-level GWAS datasets are openly accessible from the website (https://gwas.mrcieu.ac.uk/) mentioned in the main paper (Method section). Four methods for estimating causal effects were employed in our research, with the IVW method providing the primary outcome in this paper.

| **Phenotype/Trait**                 | **GWAS ID**        | **Consortium** | **Sample Size** | **Number of SNPs** | **PubMed ID/Author** |
| --------------------------------- | ----------------------------------- | ------------------ | -------------- | --------------- | ------------------ | -------------------------- |
| Exposure: Toxoplasmosis Infection |
|                                   | Anti-_T. gondii_ IgG Seropositivity | ebi-a-GCST90006925 | UKB/IEU        | 8,735           | 9,170,312          | 33204752                   |
|                                   | Anti-_T_. _gondii_ IgG Levels       | ieu-b-4910         | IEU            | 5,010           | 7,247,045          | 34804013                   |
| Outcome: Psychiatric Disorders    |
|                                   | Addiction                           | ukb-d-20552_2      | UKB (20552)    | 116,746         | 9,619,069          | Neale lab                  |
| ukb-d-20415                       | UKB (20415)                         | 2,739              | 9,575,723      | Neale lab       |
| Bipolar Disorder                  | ebi-a-GCST003724                    | PGC                | 34,950         | 9,483,147       | 27329760           |
| ieu-a-801                         | PGC                                 | 16,731             | 2,427,221      | 21926972        |
| ieu-b-41                          | PGC+UKB                             | 51,710             | 13,413,244     | 31043756        |
| ieu-b-5110                        | PGC+UKB                             | 413,466            | /              | 34002096        |
| Obsessive Compulsive Disorder     | ieu-a-1189                          | PGC                | 33,925         | 8,409,517       | /                  |
| Schizophrenia                     | ebi-a-GCST90018919                  | UKB+FinnGen        | 451,454        | 24,192,920      | 34594039           |
| ieu-b-5102                        | PGC                                 | 127,906            | /              | 35396580        |
| ieu-b-42                          | PGC                                 | 77,096             | 15,358,497     | 25056061        |
| finn-b-F5_SCHIZO                  | FinnGen                             | 218,792            | 16,380,466     | /               |
| finn-b-F5_SCHZPHR                 | FinnGen                             | 214,236            | 16,380,456     | /               |
| finn-b-KRA_PSY_

SCHIZODEL        | FinnGen                             | 218,792            | 16,380,466     | /               |
| finn-b-KRA_PSY_

SCHIZODEL_EXMORE | FinnGen                             | 176,675            | 16,380,242     | /               |
| Outcome: Risk-taking Behavior     |
|                                   | Risk-taking

Behavior               | ukb-a-241          | UKB (2040)     | 325,821         | 10,894,596         | Neale Lab                  |
| ukb-b-14147                       | UKB (2040)                          | 446,279            | 9,851,867      | Ben Elsworth    |
| ebi-a-GCST90013958                | UKB (2040)                          | 407,746            | 11,039,206     | 34017140        |
| ebi-a-GCST006810                  | UKB (2040)                          | 436,236            | 813,689        | 30271922        |

## Meta_Analysis

The meta-analysis leveraged information prodeuced from the MR analyses to comprehensively evaluate the overall effects on various psychiatric diseases and test the heterogeneity of the results.

