# Predicting the Functions of Sea Anemone Associated Bacteria with PICRUSt2
## Parker Lund, Cal Poly Humboldt, BIOL 480 Bioinformatics
- Determining the function of bacteria in host-associate microbial communities is one of the major challenges of microbial ecology research. Metagenomics can be used to look for functional genomes in the bacterial genome, however this can be cost prohibitive, especially when working with communities comprised of many bacterial species.

- A cheaper alternative is to first analyze ASVs (generated from 16S rRNA amplicon sequencing) with PICRUSt2, which predicts potential functional genes from what’s been identified already in the literature. This is useful for generating new hypotheses about the function of host-associated bacteria. One caveat is that it does not guarantee that the bacteria are performing a certain function, only that they may have the capacity for it. It may also be much more limited for taxa that are poorly described.

- I will be using the 16S rRNA sequence data generated from my anemone thermal stress experiment to investigate the functional potential of sea-anemone associated bacterial communities. I will be looking for genes associated with mitigating oxidative stress (like sodA or pqq) and comparing the abundances of these gene groups between temperature treatments. High temperatures often result in an increase in the presence of reactive oxygen species, which can damage DNA and cellular structures at high concentrations. I expect that bacterial communities at higher temperatures will also be better equipped for mitigating the presence of reactive oxygen species. The change in abundance of oxidative stress genes across temperature treatments will also be compared with the change in abundance of a general housekeeping gene. This project serves as a jumping off point for future investigations into the function of sea anemone-associated microbial communities.

## Citations
	1. Barbera, P. (2019) EPA-ng: Massively Parallel Evolutionary Placement of Genetic Sequences. Systematic Biology, 68(2), 365-269.
	2. Czech, L. (2020) Genesis and Gappa: processing, analyzing and visualizing phylogenetic (placement) data. Bioinformatics, 36(10), 3263–3265.
	3. Douglas, G.M. et al. (2020) PICRUSt2 for prediction of metagenome functions. Nature Biotechnology, 38, 685-688.
	4. Louca, S. and Doebali, M. (2018) Efficient comparative phylogenetics on large trees. Bioinformatics, 34(6), 1053–1055.
	5. Ye, Y. and Doak, T.G. (2009) A Parsimony Approach to Biological Pathway Reconstruction/Inference for Genomes and Metagenomes. PLOS Computational Biology.

<!---
pklund56/pklund56 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
