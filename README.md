another change on macbook 

# Motivation

Clinical labs are moving towards WGS. 

CNVs can be better discovered using depth coverage profiles from WGS than:  
* exome sequencing (where coverage is biased systematically by hybridization and amplification) 
* array hybridization (where probe density is sparse (1/10000bp)). 

But WGS coverage profiles are noisy, confounding the discovery of CNVs. 

The standard approach to characterize the noise is to do control experiments 
where the signal is purposefully left out.  But this costs money and time. 

Deep learning has proven successful at mapping sequence information onto 
epigenetic information. Here we tackle the potentially more challenging 
task of deep-learning a mapping from sequence to read depth. 

Any methods developed will be highly generalizable to other seq protocols, e.g., RNA-seq. 



