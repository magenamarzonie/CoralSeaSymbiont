Analysis for Coral population ecology predicts Symbiodiniaceae diversity across thermally distinct reefs <br>
Authors: Magena R. Marzonie, Matthew R. Nitschke, Line K. Bay, David G. Bourne, Hugo B. Harrison <br>

**1_Analysis.Rmd** contains all scripts required to run analyses within the manuscript. Analysis are structured as follows within the Rmd:  (use Outline tab in Rmd for easy navigating)<br>
  1. Library statistics for ITS2 type profiles/DIVs <br
  2. UPGMA trees for ITS2 type profiles/DIVs <br>
  3. Marker alignment tanglegram psba-ITS2 <br>
  4. PCoAs with UniFrac distance <br>
  5. distance-based RDAs <br>
  6. Procrustes rotation analysis <br>
  7. distance-based RDA subset models with host genetic data <br>
<br>
Other files needed to run scripts> <br>

**O_SymPortal** folder contains post-med sequence analysis of symbiont DIVs and Type Profiles which are required to run 1_Analysis <br>

**Metadata.csv** contains environmental and host species data associated with each sample. Note that 'Vial' refers to each coral individual sample collected <br>

**Metadata_mtorf.csv** contains environmental and host species data associated with each sample, with updated mtORF alignment. Both metadata files are required for 1_Analysis. Note that 'Vial' refers to each coral individual sample collected <br>

**psba txt files** are required to run the marker alignment 

**PverDart_CSS/ PmeaDart_CSS/ AcroDart_AlCluster_CSS** contains the scripts required to run host filtering These files are not needed to directly run 1_Analysis.Rmd scripts, but show the pre-filtering steps prior to importing host genetic data. <br>
