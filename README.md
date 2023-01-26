# proteins_MA
Proteins Mediation Analysis in CHRIS

- Adjusting variants for the 148 proteins have been done!
- Variants association with the plasma proteins have been done!
- There was a huge deviation for CHRIS proteomics subsamples in terms of the association of the SNPs with kidney function (eGFRw.log.Res) compared to GWAS effects magnitude -> Has to be fixed immediately. Mediation analysis has been ongoing with some sensitivity analysis of the results to find out the bug. Perhaps the difference between populations in terms of sample size is the main root of the deviation. Let's make sure!

- So far, I checked teh density/scatter/violin plots of the varians' dosage groupped by the peptited individuals and not-peptited individuals. Let's check it again and find PI's opinion. 

- In the end, we came to this conclusion that the effect differences between CHRIS 10K and subsamples with proteins have been rooted in sample size disparity.
- Next, we go for next stage of the analysis and fairly/slightly relieve the multiple testing threshold.

Dariush | 26-Jan-2023
