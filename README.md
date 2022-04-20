# data-analysis-replication

Directories

-- data = publicly available data provided by original paper authors
-- images = figures taken directly from original paper

Files

Top-Level:
-- data-analysis-replication.Rmd = main R-markdown file containing all code for replicating the original paper as well as explanatory text
-- data-analysis-replication.html = knitted R-markdown file containing finished replication project with all figures
-- Molecular Ecology - 2021 - Van Belle - Dispersal patterns in black howler monkeys Alouatta pigra Integrating multiyear.pdf = original paper

Data:
-- Adults2012.xlsx = list of all adults sampled in 2012, including sex and home group
-- GenotypeData_Dryad.csv = table of genotypes for all individuals, contains bi-allelic genotypes in "alleleA/alleleB" format; each allele is a repeat count for microsatellite loci, and each column is a locus
-- GeographicCoordinates.csv = list of all groups observed in 2012, including cartesian coordinates
-- PairwiseRelatedness_allAdultDyads_2012.xlsx = table of pairwise comparisons of all adults, with a relatedness score (estimated using Queller-Goodnight estimator) as well as information on both individuals' sex and home group; additionally, information about the dyad as a whole is included