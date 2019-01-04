# iGUIDE_manuscript_analysis
Analysis provided in the "iGUIDE: an improved pipeline for analyzing CRISPR cleavage specificity" manuscript.

For an updated version of iGUIDE, please visit https://github.com/cnobles/iGUIDE.

This repository is meant to provide the source code for the analysis provided in the above manuscript by Christopher L. Nobles, Shantan Reddy, January Salas-McKee, Xiaojun Liu, Carl H. June, J. Joseph Melenhorst, Megan Suhoski, Yangbing Zhao, and Frederic D. Bushman.

Abstract:
Genome engineering methods have advanced greatly with the development of programmable nucleases, but methods for quantifying on- and off-target cleavage sites and associated deletions remain nascent. Here, we report an improvement of the GUIDE-seq method, iGUIDE, which allows filtering of mispriming events to clarify the true cleavage signal. Using iGUIDE, we specify the locations of Cas9-guided cleavage for four guide RNAs, characterize associated deletions, and show that naturally occurring background DNA double strand breaks are associated with open chromatin, gene dense regions, and chromosomal fragile sites. iGUIDE is available from https://github.com/cnobles/iGUIDE.

To run the analysis, run the R-code blocks from the 'manuscript_figures.archive.Rmd' file. It will pull from already processed and compressed data in the rest of the repository to generate the figures from the manuscript. This repository also contains a final processing dataset from the manuscript. Anyone can use this data rather than reprocessing with the iGUIDE software from the SRA submission (BioProject: PRJNA506241). There is no certainty that reprocessing will yeild the same results if the version of the iGUIDE software is different (data processed with version 0.9).
