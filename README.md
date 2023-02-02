## Phenotype description
A direct measure of non-suicidal self-injury is not provided by the UK Biobank; however, we derived this phenotype using information from the UK Biobank’s on-line “Thoughts and Feelings” mental health questionnaire. The questionnaire asked individuals “*Have you deliberately harmed yourself, whether or not you meant to end your life?*” (Data-Field 20480, N = 137,969), and those who answered “Yes” (N = 5,924) were then asked in a follow-up question, “*Have you harmed yourself with the intention to end your life?*” (Data-Field 20483). Individuals who answered yes to both questions (N = 3,056), indicating self-harm with suicidal intent, were excluded from our analyses. After quality control (see below), we were left with a remaining sample size of 133,620 individuals (N cases = 2,845). GWAS was only performed in individuals with European genetic ancestry using the [genetic ancestry assignments returned by Pan-UK Biobank](https://pan.ukbb.broadinstitute.org/docs/qc/index.html#ancestry-definitions).

## Download Instructions
Summary statistics are available to download via box using the link below. 

[download](https://wustl.box.com/s/t23oxqaysi69znerti1col34372pywi1) 

## Citation for studies using this data
Please cite the following preprint:

[Colbert, S. M.C., Mullins, N., Chan, G., Meyers, J. L., Schulman, J., Kuperman, S., ... & Johnson, E. C. (2022). Polygenic contributions to suicidal thoughts and behaviors in a sample ascertained for alcohol use disorders. medRxiv.](https://www.medrxiv.org/content/10.1101/2022.08.18.22278943v1)

## File description

**Please note that association results are with regard to Allele2.**
The file contains the raw summary statistics which have not been filtered in any way. We provide EAF and imputation info incase those using the summary statistics wish to perform any filtering. 

| Column | Description |
| --- | --- |
| CHR | chromosome |
| POS | genome position |
| rsid | rs ID for variant |
| Allele1 | allele 1 |
| Allele2 | allele 2 |
| AF_Allele2 | allele frequency of allele 2 |
| imputationInfo | imputation info. If not in dosage/genotype input file, will output 1|
| N | sample size |
| BETA | effect size of allele 2 |
| SE | standard error of BETA |
| p.value | p value (with SPA applied for binary traits) |
