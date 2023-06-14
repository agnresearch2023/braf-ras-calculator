BRAFV600E & RAS MUTATION PREDICTION MODEL
=========================================

INTRODUCTION
------------

Papillary thyroid carcinoma (PTC) is the most common type of thyroid carcinoma and comprises 80–85% of thyroid gland malignancies. PTC has various variants which generally shows a good prognosis and non-aggressive, with a 10-year survival rate of 90–95%. However, some PTC variants have a worse and more aggressive prognosis, for example tall cell, columnar, oncocytic, and solid variants. These variants often show lymph node metastases, and are resistant to I-131 radio-ablation therapy.

Various gene mutations play a role in the developement of PTC and are associated with tumor’s biological behavior as well as typical clinicopathological features. These mutations can occur during early and late tumor formation. In its earlier stages, tumorigenesis is caused by BRAFV600E and RAS mutations, which are mutually exclusive and leads to well-differentiated carcinomas. BRAFV600E is the most common mutation in PTC and has a 2.7 times greater risk of recurrence compared to without BRAFV600E mutation. RAS mutation is associated with low aggressiveness and have a good response to therapy.

Genetic mutation in PTC activates the mitogen-activated protein kinase (MAPK) pathway. Mutant RAS and BRAFV600E will activate this pathway autonomously and cause an increase in phosphorylated-extracellular signal-regulated kinase (pERK1/2). Phospho-specific antibody that detects pERK1/2 is used to assess MAPK pathway activity. BRAFV600E mutation leads to strong pERK1/2 activation, whereas RAS mutation leads to weaker pERK1/2 activation. This causes differences in the phenotype and biologic behavior of PTC. Histological parameters that can determine tumor biologic behavior are variant, capsule, nuclear score, multifocality, lymphovascular invasion (LVI), peri-thyroidal tissue invasion and lymph node metastases.

The Cancer Genome Atlas divides the molecular classification of mutations in PTC into BRAF-like and RAS-like because of the differences in biological traits of the two groups. BRAF-like PTC requires more aggressive management strategies such as total thyroidectomy and radio-ablation as well as more stringent patient follow-up, whereas RAS-like PTC is indolent and should not be overtreated. Molecular examination is required to differentiate the two types, however such examination is not routinely carried out in Indonesia due to limited resources. Histopathological appearance is thought to be able to differentiate the two, but until now this has not been studied. To overcome this problem, predictive indicators of BRAFV600E and RAS gene mutations in PTC are needed using clinical profiles, histopathological characteristics and pERK1/2 protein expression.

ABOUT BRAFV600E & RAS MUTATION PREDICTION MODEL
-----------------------------------------------

This prediction model was obtained from a research conducted by dr. Agnes Stephanie Harahap, Sp.PA, Subsp. H.L.E.(K). The research is an analytic cross-sectional study conducted in RSUPN dr. Cipto Mangunkusumo (RSCM). The research samples which met inclusion criteria and pass the exclusion criteria were divided into 3 groups, namely the BRAFV600E, RAS, and non BRAFV600E-non RAS mutation groups. Each group has a minimum of 40 samples based on the rule of thumb principle and are taken from RSCM in January 2019–August 2022 and Siloam MRCCC Hospital in 2022.

Clinical and histopathological data were taken from the archives of the Department of Anatomical Pathology and medical records. Reassessment of all histopathological characteristics (tumor size, nuclear score, capsule, histopathological variant, multifocality, LVI, peri-thyroidal tissue invasion, lymph node metastases) was carried out by three pathologists separately and was blinded to diagnosis and mutation status. The results of inter-observer agreement using Kappa showed good outcomes.

This study used polymerase chain reaction (PCR) examination and DNA sequencing on formalin-fixed paraffin embedded tissue (FFPE) specimens to detect gene mutations. The FFPE containing the most adequate tumor tissue was cut into 3–8 pieces with the thickness of 5–10 µm. DNA extraction was performed with the QIAamp DNA FFPE Tissue Kit (Qiagen, USA). PCR examination was performed with specific primers for BRAF and RAS gene amplification. DNA sequencing used the ABI PRISM 3730xl Genetic Analyzer (Applied Biosystems, USA) with the Sanger method. BRAFV600E, NRAS, HRAS and KRAS mutations were confirmed using the Single Nucleotide Polymorphism ID (SNPID) sequence comparison tool available on NCBI website (http://www/ncbi.nlm.nih.gov/SNP) and using the Basic Local Alignment Search Tool (BLAST), and was then manually confirmed using electrophoregram. Immunohistochemical (IHC) staining of pERK1/2 was performed manually and the results of the staining were assessed quantitatively as a percentage using Image J software.

The data normality test was performed using Kolmogorov-Smirnov test. Numerical data were presented in median and minimum–maximum, and analyzed using Mann Whitney test. Categorical data were analyzed using the Chi square test. The pERK1/2 cut off was determined by reference data. The pERK1/2 cut off of 10% was chosen based on Hosmer Lemeshow test results consideration, the area under curve (AUC) and 95% CI precision. The multivariate analysis was done with multinomial logistic regression with the backward conditional method. Scores were obtained in two stages, namely by dividing the coefficient B by the standard error (SE) and dividing the B/SE results by the smallest B/SE results. Through these stages, two prediction models were acquired, namely BRAFV600E and RAS mutations prediction models. Follow-up analysis was carried to determine the probability of each scoring systems to predict mutations. This is then followed with application of the two prediction models to all samples and multinomial analysis of combined BRAFV600E and RAS prediction models.

The BRAFV600E prediction model was created using a core score variable of 3, encapsulated and aggressive variant types (tall cell, oncocytic and solid), each of which gives a score of 1. The expression variable pERK1/2 > 10% gives a score of 2. The analysis shows that the higher the total score, the greater the probability that the KTP shows the BRAFV600E mutation. The highest probability of 82% is obtained for the highest total score of 5. KTP with the BRAFV600E mutation shows a more aggressive temperament. TCGA has mapped various types of mutations that have a similar outcome to the BRAFV600E mutation so that they are grouped into the BRAFV600E-like classification.

The BRAFV600E prediction model can show a score with a medium probability, making management decisions difficult. Given the possibility that KTP with the BRAFV600E mutation still exists, this probability value cannot be ignored. Therefore, this study suggests using the BRAFV600E and RAS prediction models simultaneously in daily practice.

The RAS prediction model includes follicular variant variables and pERK1/2 expression > 10%, each giving a score of 1. Just like BRAFV600E, the higher the total model score, the higher the probability that KTP shows RAS mutations. In this study the highest probability analysis of 70% is obtained if the total score is 2. TCGA maps various mutations belonging to the RAS-like classification.

The use of the RAS prediction model to complement the BRAFV600E prediction model is expected to increase confidence in making more personalized treatment decisions.

DISCLAIMER
----------

Even though internal validation has been carried out and results are in accordance with estimates, this predictive model cannot be directly applied in daily practice because observational studies alone cannot change clinical practice and standard operating procedures. Furthermore, external validation is needed to prove the relationship between this predictive model and aggressive tumor behavior such as survival, metastasis and recurrence outcomes.
