# PedigreeWrapper
PedigreeWrapper is a wrapper for the single nucleotide polymorphism (SNP) genotype simulator PedigreeSim (https://www.wur.nl/en/show/Software-PedigreeSim.htm). It is written in R (version 3.5.2), and provides gamete selection functionality, allowing the user to apply a selection pressure of specified strength at a specified position against gametes containing a particular parental allele from a biparental cross. 

The wrapper also provides parallelization, allowing many simualtions to be performed simultaneously via the mclapply R function. The wrapper should be placed in your PedigreeSim directory. It produces a single seed descent population structure for a specified number of filial generations. 
