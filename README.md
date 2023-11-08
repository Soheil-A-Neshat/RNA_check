# RNA_check
A package for rRNA and tRNA annotation on metagenome assembled genomes (MAGs)  
Requires the following packages to run:
  1. barrnap v0.9
  2. tRNAScan-SE v2.0.12
  3. Infernal v1.1.4

# Installation

You can just RNA_check from GitHub and run it directly.

Retrieve the files:  
git clone https://github.com/Soheil-A-Neshat/RNA_tag.git  
Create a Conda environment with prerequisites using the RNA_check.yml file:  

conda env create -n RNA_check -f RNA_check.yml  
conda activate RNA_check  
Then, run RNA_check:  
RNA_check -h  
# Citation
Please cite "Neshat, S. A. (2022). Microbiome studies on anaerobic digestion using genome–resolved multi–omics."
