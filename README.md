# local-compartment identification
Rscript for chromosome block-wise compartment identification.
## Depedency

R (>3.0) with rioja package.

CscoreTool
awk
## Introduction
This scirpt use HiC-Pro format result to identify local compartment in plant genome.
## Usage
Rscript call_local_compartment.R bin_ord resolution interaction.matrix all_valid_data out_prefix 
