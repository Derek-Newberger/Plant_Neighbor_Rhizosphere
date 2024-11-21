The README.docx contains descriptions for the uploaded files.

File and code repository for the manuscript entitled "Effect of intra- and inter-specific plant interactions on the rhizosphere microbiome of a single target plant at different densities" by Newberger et al. (2024).

Abstract: Root and rhizosphere studies often focus on analyzing single-plant microbiomes, with the literature containing minimum empirical information about the shared rhizosphere microbiome of multiple plants. Here, the rhizosphere of individual plants was analyzed in a microcosm study containing different combinations and densities (1-3 plants, 24 plants, and 48 plants) of cover crops: Medicago sativa, Brassica sp., and Fescue sp. Rhizobacterial beta diversity was reduced by increasing plant density for all plant mixtures. Interestingly, plant density had a significant influence over beta diversity while plant diversity was found to be a less important factor since it did not have a significant change. Regardless of plant neighbor identity or density, a low number of rhizobacteria were strongly associated with each target species. Nonetheless, a few bacterial taxa were shown to have conditional associations such as being enriched within only high plant densities, which may alleviate plant competition between these species. Also, we found evidence of bacterial sharing of nitrogen fixers from alfalfa to fescue. Although rhizosphere bacterial networks had overlapping bacterial modules, the modules showing the largest percentage of the network changed depending on plant neighbor. In summary, this study found that for the most part plants maintained their rhizosphere microbiome despite escalating plant-plant competition.

Keywords: rhizosphere, plant-plant interactions, microbiome, bacteriome, bacteria, cover crops, plant competition

R Markdown files:

Networks.Rmd
-This file has the Rcode for the network analysis that were ran and then served as inputs for the Gephi program. This Rmd files requires myFunctions.R, EMU.rel_abund.finalRhizoDD1.csv, demultiplex_Rhizo_DD1.xlsx, EMU.rel_abund.finalRhizoDD2.csv, demultiplex_Rhizo_DD2.xlsx.

RhizoBFDiffAbund.Rmd
-Rhizosphere brassica fescue differential abundance. This file has the Rcode for all the differential abundance comparisons made. Not all differential abundance comparisons were found to be interesting enough to be put into the manuscript itself. The beta dispersion values were also calculated in this file and several data visualization of the beta dispersion were made, but it was decided that a table with values coupled with statistics (in the RhizoDD_StatsDisper.Rmd file) were more valuable form to convey the information. CAP scale analysis was also performed, but did not show new or interesting results. This Rmd file requires myFunctions.R, EMU.rel_abund.finalRhizoDD1.csv, demultiplex_Rhizo_DD1.xlsx, EMU.rel_abund.finalRhizoDD2.csv, demultiplex_Rhizo_DD2.xlsx.

RhizoDD_StatsDisper.Rmd 
– Rhizosphere of plant density and diversity Statistics for the beta dispersion. This file has the Rcode that runs the statistics for the beta dispersion values. It shows that plant density was a more influential factor than plant diversity when it came to the beta dispersion values. This Rmd file requires Beta_Disper.csv.

Supporting files:

Beta_Disper.csv
-Beta dispersion values that are required for RhizoDD_StatsDisper.Rmd to run.

EMU.rel_abund.finalRhizoDD1.csv
-the relative abundance by taxa of the first sequence run.

demultiplex_Rhizo_DD1.xlsx
-the metadata for the first sequence run. Name was the sample label, these samples were rhizosphere soil labeled as “soil”. H2O was the water control which was extracted with the samples. For each PCR, a new water control sample was added. Zymo is the mock community. Letter combinations only use A (alfalfa), B (brassica), and F (fescue). If the sample has only one capitalized letter, that indicates from which plant the rhizosphere sample was collected from. For example, name: 10Abf48 was a sample from the alfalfa rhizosphere, but grown in the same pot with brassica and fescue. The term “other” was used so that differential abundance can be ran since it is restricted to only two variables. The Numbers 1, 24, and 48 refer to the plant count total in each pot. Plant density was equally distributed by plant mixture, as in Ba24 has 12 brassica plants, and 12 alfalfa plants, with a total of 24 plants. In column “Network”, the “P” means polyculture and the “M" means monoculture. Under column name, and “R” denotes a test replicate of another sample.

EMU.rel_abund.finalRhizoDD2.csv
-the relative abundance by taxa of the second sequence run.

demultiplex_Rhizo_DD2.xlsx
-the metadata for the second sequence run. Name was the sample label, these samples were rhizosphere soil labeled as “soil”. H2O was the water control which was extracted with the samples. For each PCR, a new water control sample was added. Zymo is the mock community. Letter combinations only use A (alfalfa), B (brassica), and F (fescue). If the sample has only one capitalized letter, that indicates from which plant the rhizosphere sample was collected from. For example, name: 10Abf48 was a sample from the alfalfa rhizosphere, but grown in the same pot with brassica and fescue. The term “other” was used so that differential abundance can be ran since it is restricted to only two variables. The Numbers 1, 24, and 48 refer to the plant count total in each pot. Plant density was equally distributed by plant mixture, as in Ba24 has 12 brassica plants, and 12 alfalfa plants, with a total of 24 plants. In column “Network”, the “P” means polyculture and the “M" means monoculture. Under column name, and “R” denotes a test replicate of another sample.

PLOS_One_SupplementaryMaterial
-All supplementary tables submitted to PLOS ONE.

Manter MinION Protocol Jan22
-The modified protocol used in the Manter lab at the time of sequencing the full 16S region.

myFunctions.R
-An R file with code that was made by the author DM.
![image](https://github.com/user-attachments/assets/f8741e8a-b7d2-4734-9bc0-305f6ab1d622)
