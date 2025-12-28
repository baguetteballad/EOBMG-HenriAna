############
EOBMG25/26
############

## Overview

This repository contains a collection of Bash commands and R scripts used to process, analyze, and manipulate biological datasets as part of the EOBMG curricular unit in our bachelor's program in Biology - Branch of Molecular Biology & Genetics @FCUL.
Specifically, it includes utilities for sample organization and preparation for Galaxy - RepeatExplorer manuevering, plotting repeats' abundances in the repeatome, phylogenetic analysis, genome size estimation and more.
We focused on two different big groups of samples, namely relating to lupins and cichlids, however, these tutorials can, naturally, be reused for other biological datasets.

## Contents

Each file (numbered 1 to 8) contains scripts corresponding to a specific step in the workflow:
- 1: Shell commands (Bash) to subsample and organize datasets;
- 2: Windows PowerShell commands to save Galaxy's output locally, alongside more bash commands;
- 3: RStudio script for plotting repeats' abundances in the repeatome;
- 4: Bash commands to proceed with genome size estimation;
- 5: RStudio script for histogram analysis' and concluding genome size estimation;
- 6: Downloading SRA runs referrent to public datasets and importing them to the WSL server;
- 7: RStudio script for making and plotting Newick-formatted trees;
- 8: RStudio script for linear correlations.

## Tech Stack

This repository includes:

- **Bash / Shell scripting;**
- **Windows PowerShell;**
- **R / RStudio scripts;**
- Standard command-line utilities.

## Getting Started

To begin using this project:

1. **Clone the repository**  
   ```sh
   git clone https://github.com/baguetteballad/EOBMG-HenriAna.git
   cd EOBMG-HenriAna
