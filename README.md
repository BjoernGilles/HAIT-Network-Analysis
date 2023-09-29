# HAIT-Network-Analysis
# R-Scripts used in the ublication "Defining Human-AI Teaming the Human-Centered Way: A Scoping Review and Network Analysis" (doi: 10.3389/frai.2023.1250725)

This repository contains several R markdown notebooks that were used to produce the publication.
To replicate the workflow, run the notebooks listed below in the correct order, chunk by chunk. If random processes or longer processing times are involved, our R workspace is also provided.

1. createBiblioDf/Rayyan2bibliodf.Rmd : Merges the in Rayyan included article data from Web of Science and Scopus into a bibliometrix-Dataframe
2. MergeCRs/unify_references.Rmd : Includes algorithms to extract reference information from WoS and Scopus and a function that uses this information to create a unified format.
3. NetworkAnalysis/network_analysis.Rmd : Performs bibliometric coupling analysis using the new reference format as a basis for edge formation.
4. SimulateClusters/Simulate_Cluster.Rmd : Replicates clustering solutions to check for stability problems.

# Package versions:

All loaded package versions and other information relevant to replication can be found in the session.txt file in each folder.
