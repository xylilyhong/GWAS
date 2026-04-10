# GWAS
This is a genome-wide association study (GWAS) on the relationship between obesity, depression, and gastroesophageal reflux disease (GERD)

### Raw data sets (accessed from the Integrative Epidemiology Unit (IEU) OpenGWAS database https://opengwas.io): 

(1)	GERD_UKBB_QSKIN.gwas.gz

(2)	whr.giant-ukbb.meta-analysis.combined.23May2018.txt.gz

(3)	whradjbmi.giant-ukbb.meta-analysis.combined.23May2018.txt.gz

(4)	Meta-analysis_Locke_et_al+UKBiobank_2018_UPDATED.txt.gz

(5)	pgc-mdd2025_no23andMe_eur_v3-49-24-11.tsv.gz

(6)	GIANT_2015_WHR_COMBINED_EUR.txt.gz

(7)	GIANT_2015_WHRadjBMI_COMBINED_EUR.txt.gz

(8)	SNP_gwas_mc_merge_nogc.tbl.uniq.gz

(9)	daner_pgc_mdd_meta_w2_no23andMe_rmUKBB.gz

(10) LD reference data

### Primary analyses

WHR on GERD: exposure – (2), outcome – (1)

Depression on GERD: exposure – (5), outcome – (1)

WHR on Depression: exposure – (2), outcome – (5)

GERD on Depression: exposure – (1), outcome – (5)

GERD on WHR: exposure – (1), outcome – (2)

Depression on WHR: exposure – (5), outcome – (2)

### Sensitivity analyses A, with different measures of adiposity

WHRadjBMI on GERD: exposure – (3), outcome – (1)

GERD on WHRadjBMI: exposure – (1), outcome – (3)

WHRadjBMI on Depression: exposure – (3), outcome – (5)

Depression on WHRadjBMI: exposure – (5), outcome – (3)

BMI on GERD: exposure – (4), outcome – (1)

GERD on BMI: exposure – (1), outcome – (4)

BMI on Depression: exposure – (4), outcome – (5)

Depression on BMI: exposure – (5), outcome – (4)

### Sensitivity analyses B, with earlier GWAS not including UKB to mitigate potential bias

WHR on GERD: exposure – (6), outcome – (1)

Depression on GERD: exposure – (9), outcome – (1)

WHR on Depression: exposure – (6), outcome – (9)

GERD on Depression: exposure – (1), outcome – (9)

GERD on WHR: exposure – (1), outcome – (6)

Depression on WHR: exposure – (9), outcome – (6)

WHRadjBMI on GERD: exposure – (7), outcome – (1)

GERD on WHRadjBMI: exposure – (1), outcome – (7)

WHRadjBMI on Depression: exposure – (7), outcome – (9)

Depression on WHRadjBMI: exposure – (9), outcome – (7)

BMI on GERD: exposure – (8), outcome – (1)

GERD on BMI: exposure – (1), outcome – (8)

BMI on Depression: exposure – (8), outcome – (9)

Depression on BMI: exposure – (9), outcome – (8)

### Further analyses

Multivariable MR: WHR and depression on GERD, WHR and GERD on depression, depression and GERD on WHR

Repeat univariable MR with non-pleiotropic variants