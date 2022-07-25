## Phenotype description
A direct measure of non-suicidal self-injury is not provided by the UK Biobank; however, we derived this phenotype using information from the UK Biobank’s on-line “Thoughts and Feelings” mental health questionnaire. The questionnaire asked individuals “*Have you deliberately harmed yourself, whether or not you meant to end your life?*” (Data-Field 20480, N = 137,969), and those who answered “Yes” (N = 5,924) were then asked in a follow-up question, “*Have you harmed yourself with the intention to end your life?*” (Data-Field 20483). Individuals who answered yes to both questions (N = 3,056), indicating self-harm with suicidal intent, were excluded from our analyses. After quality control (see below), we were left with a remaining sample size of 133,620 individuals (N cases = 2,845). GWAS was only performed in individuals with European genetic ancestry using the (genetic ancestry assignments returned by Pan-UK Biobank)[https://pan.ukbb.broadinstitute.org/docs/qc/index.html#ancestry-definitions].

## Download Instructions
Summary statistics are available to download via box using the link below. 

## Citation for studies using this data
To be posted as soon as a pre-print is made available

## File description

**Please note that association results are with regard to Allele2.**

| Column | Description |
| --- | --- |
| CHR | chromosome |
| POS | genome position |
| rsid | rs ID for variant |
| SNPID | variant ID |
| Allele1 | allele 1 |
| Allele2 | allele 2 |
| AC_Allele2 | allele count of allele 2 |
| AF_Allele2 | allele frequency of allele 2 |
| imputationInfo | imputation info. If not in dosage/genotype input file, will output 1|
| N | sample size |
| BETA | effect size of allele 2 |
| SE | standard error of BETA |
| Tstat | score statistic of allele 2 |
| p.value | p value (with SPA applied for binary traits) |
| p.value.NA | p value when SPA is not applied (only for binary traits) |
| Is.SPA.converge | whether SPA is converged or not (only for binary traits) |
| varT | estimated variance of score statistic with sample relatedness incorporated |
| varTstar | variance of score statistic without sample relatedness incorporated |
| AF.Cases | allele frequency of allele 2 in cases (only for binary traits and if --IsOutputAFinCaseCtrl=TRUE) |
| AF.Controls | allele frequency of allele 2 in controls (only for binary traits and if --IsOutputAFinCaseCtrl=TRUE) |
