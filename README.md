LDSC (LD SCore) v 1e-4
======================

Copyright (c) 2014 Brendan Bulik-Sullivan & Hilary Finucane

(Warning: under very active development)

What can I do with LDSC?
---------------------

1. Estimate LD Score
2. Quantify the inflation in GWAS test statistics from confounding bias.
3. Estimate heritability from GWAS summary statistics.
4. Estimate partitioned heritability from GWAS summary statistcs.
5. Estimate genetic covariance and correlation from GWAS summary statistics.

Contact
-------

Brendan Bulik-Sullivan, bulik@broadinstitute.org

Citations
---------

Bulik-Sullivan, et al. LD Score Regression Distinguishes Confounding from Polygenicity in Genome-Wide Association Studies.
doi: http://dx.doi.org/10.1101/002931

(preprint: http://biorxiv.org/content/early/2014/02/21/002931)


What is LD Score?
--------------

LD Score is a measure of the amount of linkage disequilibrium (LD) around a SNP. 
LD Score allows one to properly take LD into account when attempting to make 
inferences about the genetic architecture of complex disease using GWAS summary 
statistics.


Requirements
------------

1. Python 2.7
2. argparse 1.2.1
3. bitarray 0.8.1
4. numpy 1.8.0
5. pandas 0.13.1
6. scipy 0.10.1

