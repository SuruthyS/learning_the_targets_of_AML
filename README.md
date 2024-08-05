# learning_the_targets_of_AML

This repository consists of the data and code used in the manuscript "Learning the Therapeutic Targets of Acute Myeloid Leukemia through Multiscale Human Interactome Network and Community Analysis".

## Folders

### Baseline_Metrics_Results
Results from using four baseline metrics (L2 norm, L1 norm, Canberra distance, Cosine similarity, and Correlation distance) and the diffusion profiles of the drugs and acute myeloid leukemia (AML).
### communities
Data from running CoDA and CRank is included in this folder with the data generated from its analysis in "Detecting_Proteins_and Biological_Functions_in_Prioritized_Communities".
### images
Basic images of the networks, tables, and supplementary tables that are presented in the manuscript.
### networks
Network files (.graphml) that were constructed using Cytoscape (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC403769/) fo the selected candidates.
### top_4
Data of diffusion profiles and treatment importance values that are formatted for use in generating networks in Cytoscape.
### vist_freq_drug_disease
Contains the results of the visitation frequency anlaysis of the possible candidates and AML from the multiscale interactome network which is preformed in "using_the_multiscale_interactome".

## Code

### Detecting_Proteins_and Biological_Functions_in_Prioritized_Communities
Code that is used to anzlyze the results from CoDA (https://github.com/snap-stanford/snap/tree/master/examples/coda) and CRank (https://github.com/mims-harvard/crank) to count the frequency of the top proteins and biological functions of the candidates in the highly prioritized communities in the multoscale interactome network (CRank>80%).

### using_the_multiscale_interactome
Code that is used to run the multiscale interactome network (https://github.com/snap-stanford/multiscale-interactome) and analyzing the resutls for AML.

