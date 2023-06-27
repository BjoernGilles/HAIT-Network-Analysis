# HAIT-Network-Analysis
# R-Scripts used in the Publication {Title} {Doi}


To replicate the used workflow, run scripts in the following order:
1. Rayyan2bibliodf.Rmd # Merges in Rayyan included article data from Web of Science and Scopus into a bibliometrix-Dataframe
2. unify_references.Rmd # Includes algortihms to extract Reference information from WoS and Scopus and a function that uses this information to create a unified format.
3. network_analysis.Rmd # Conducts bibliometric coupling analysis using the new reference format as basis for edge formation.
4. Simulate_Cluster.Rmd # Replicates clustering solutions to check for stability issues.
5. Simulate_false_positives.Rmd # Uses resampling to estimate the liklihood of false-positives being introduced in the reference formatting algorithm.

Since some operations include random processes and/or require longer computation times, R-workspace Images are included and can be loaded to view our exact results.

# Package Versions:

All loaded package versions and other information relevant for replication can be found in the file "session.txt" in each folder.
