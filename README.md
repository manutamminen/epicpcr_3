# epicPCR experiment April 25 2021

The aim of this experiment was to
1. Test the effect of magnetic size selection of the polyacrylamide beads on the reaction parameters
2. Test the idea of internal molecular standards

The following samples are included:

- Rhodomonas cells
- Rhodomonas + frozen wastewater
- Frozen wastewater
- Rhodomonas cells (beads size selected using magnetic capture)
- Rhodomonas + frozen wastewater (beads size selected using magnetic capture)
- Frozen wastewater (beads size selected using magnetic capture)
- Rhodomonas cells + molecular standards
- Rhodomonas + frozen wastewater + molecular standards
- Frozen wastewater + molecular standards

Raw data available at https://zenodo.org/record/4725295

Lab protocols available at https://github.com/manutamminen/epicpcr_3/blob/main/docs/protocols.md

Summary of the results available at https://github.com/manutamminen/epicpcr_3/blob/main/docs/index.md


# Building

## Dependencies

- Snakemake
- VSEARCH
- SINA
- FastTree
- Tidyverse

Download the raw data into data/raw.

Start the processing pipeline by invoking `snakemake --cores all report`.



