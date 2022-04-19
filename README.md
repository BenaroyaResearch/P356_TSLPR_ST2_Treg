# P356_TSLPR_ST2_Treg

# Differential roles of TSLP and IL-33 in regulation of Treg cells in progression of colorectal cancer

The code here is to do differential expression and gene set enrichment analyses 
between different Treg subpopulations and between mice with and without tumors.

## Installation

Install the libraries used in the script and run the code in R. One library (apird) is publicly unavailable
and used to access data from an internal Benaroya Research Institute database. Users without access to this library
and database can access the data from the GEO database with accession number GSE173124 and edit the code to read 
the data from the downloaded files.

## Usage

The variables (anno, libs, counts) will not be able to be generated by public users without access to apird, and thus
the data in those variables must come from GSE173124. "anno" should contain the metadata for the sequencing libraries, and
"counts" should contain the read counts downloaded from GEO.

