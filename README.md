# RNA_check
A package for rRNA and tRNA annotation on metagenome assembled genomes (MAGs)  
Requires the following packages to run:
  1. barrnap v0.9
  2. tRNAScan-SE v2.0.12
  3. Infernal v1.1.4

# Installation

You can just RNA_check from GitHub and run it directly.

Retrieve the files:  
git clone https://github.com/Soheil-A-Neshat/RNA_check.git  
Create a Conda environment with prerequisites using the RNA_check.yml file:  

conda env create -n RNA_check -f RNA_check.yml  
conda activate RNA_check  
Then, run RNA_check:  
  
RNA_check -h  

# Usage
./RNA_check [OPTIONS] 
options:  
-h     Print this Help  
-i     Path to MAGs fasta directory  
-x     MAGs format (default: fa)  
-r     Path to tRNAScan-SE output directory (containing .o files)  
-t     Path to barrnap output directory (containing gff files)  
-o     Output directory  

* RNA_check by default uses all available cpus (threads)
* Can either provide the MAGs fasta directory or rRNA and tRNA annotation directories.
* If provide both options RNA_check will ignore the annotation directories and will do the annotation.

# Citation
Please cite "Neshat, S. A. (2022). Microbiome studies on anaerobic digestion using genome–resolved multi–omics."
