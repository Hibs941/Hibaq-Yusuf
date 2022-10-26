# Hibaq-Yusuf

> library(MRInstruments)
> library(TwoSampleMR)
> ao <- available_outcomes()
> exposure_dat <- extract_instruments(c('ukb-b-7460'))
> exposure_dat <- clump_data(exposure_dat)
Clumping ukb-b-7460, 14 variants, using EUR population reference
> data <- read.table("C:/Users/Oem/Documents/Dissertation HY/Thyroid_Cancer_Meta_Analysis_2016.txt", header = TRUE)
Extracted SNPs
Calculated Beta = log(OR)
Calculated Z Score from mean and standard deviation from beta, then calculated standard error. > dat <- harmonise_data(exposure_dat, thyca_smoking_outcome_data, action = 3). Harmonising Pack years adult smoking as proportion of life span exposed to smoking || id:ukb-b-7460 (ukb-b-7460) and thyroid cancer (Thyroid_Cancer_Meta_Analysis_2016). Removing the following SNPs for being palindromic: rs78630486, rs9358909. Removing the following SNPs for incompatible alleles: rs7933830
> mr_results <- mr(dat). Analysing 'ukb-b-7460' on 'Thyroid_Cancer_Meta_Analysis_2016'. Error in lm.wfit(x, y, w, offset = offset, singular.ok = singular.ok,  : NA/NaN/Inf in 'x'
