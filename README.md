# dhx9_yass_analysis

This repository contains the YASS-based analyses performed for DHX9 uvCLAP and FLASH peaks, as performed for

Aktaş, T. et al. DHX9 suppresses RNA processing defects originating from the Alu invasion of the human genome. Nature 544, 115–119 (2017).

Script `yass_calculate_pairs.ipynb` calculates pairs that are inverse to each other, does a minimal cleanup and exports the alignments as bed12 format using script `yass_reverse_repeats_to_bed12.R`. Script `yass_calculate_pairs.ipynb` contains all further analysis of the calculated pairs.
