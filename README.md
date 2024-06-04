# Biopython NCBI Gene Function Extraction
This repository contains a Python script that uses the Entrez module from the Biopython library to fetch gene functions from the NCBI database. The script reads a list of gene IDs from a CSV file and writes the gene IDs along with their functions to a text file.
# Requirements
- Python 3.x
- Biopython library
# Installation
* To install the Biopython library, use the following command:
- pip install biopython
# Usage
* Prepare a CSV file containing a list of gene IDs. Each row should contain a single gene ID.
* Run the script with the CSV file as input and specify the output text file.
* Make sure to set your email address in the script before using the Entrez module, as it is required by NCBI. Replace the placeholder email with your actual email address
