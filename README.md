# rhumba

A collection of snakemake pipelines 

Need a workflow for identifying potential modification sites using the RNaseL WT and KO data, as well as our current franken-IVT.

Sequence

Step 1: basecalling

Step 2: QC

Step 3: graphmap sensitive alignment

Step 4: csv generation

Step 5: identify genes w/ sufficient reads for analysis
      Step 5b: readouts of ORF associated with genes

Step 6: difference in q-score, insertions, deletions, and mismatch graphs w/ notated ORF

# Step 7 and 8 may be in different order - align graphs with IGV, then select motifs

Step 7: align standout signal motifs with IGV

Step 8: readout of difference in signal aligned with location in IGV

Step 9: readout of sites with anticipated step 6 signal motifs aligned with anticipated and (previously)defined bases at site on IGV
