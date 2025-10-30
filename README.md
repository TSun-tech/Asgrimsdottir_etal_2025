# Asgrimsdottir_etal_2025

## Repository summary

This repository contains analysis code for TREX single-cell barcode tracing transcriptomic data from Asgrimsdottir et.al. 2025 manuscript.

The single-cell barcode tracing data utilized lentiviral delivered barcode library (15nt) to ESC derived dopaminergic cells. BC tracing system was previous developed by collaborator (Ratz et al. 2022 NatNeurosci).
Detailed barcode delivery and seuqnecing protocol is described in the manuscript.

Analysis followed standard scRNA-seq alignment, in combination with reference of the barcode library.

## Main contents

- Preprocessing of bacode tracing data using TREX system 
- Single-cell transcriptome profile quality control and outlier (low quality cells) filter
- Cell population and subpopulation annotation based on cluster markers
- Further observation of clone ID expansion, and their connection based on the progenitor origins
- Connection between day 17 and day 24 cells based on shared clonal IDs. Connections were observed on subpopulation level.
- Integrative and pseudotime trajectory analysis of current dataset with Braun et.al. 2023 Science data (midbrain subset)
