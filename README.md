# Gene Protein Sequence Retrieval Tool

## Overview

This project is a Python script designed to retrieve protein sequence in FASTA format from UniProt for a list of genes across multiple organisms
The retrieved data includes UniProt IDs, amino acid lengths, and the corresponding protein sequences
The script outputs the results in CSV format and logs genes that are not found in UniProt

## Key Features

- Retrieve protein sequences in FASTA format from UniProt based on gene and organism input
- Filters results to match specific organisms
- Logs unavailable genes and stores them in a separate CSV file

## Prerequisites

Before running the script, ensure you have the following installed:

- Python
- Required Python packages: pip install bioservices
- Input files:
    1. Create a genes.txt file containing a list of genes, one per line
    2. Create an organisms.txt file containing a list of organisms, one per line
 
##  License
This project is licensed under the MIT License
