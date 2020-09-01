# INTVD: Intelligent Assistance Meets Artificial Intelligence in Vulnerability Detection

Despite the successes of machine learning-based vulnerability detection (VD) models, they are still limited to providing only the decision on whether a given code is vulnerable or not, without any details on what part of the code is relevant to the detected vulnerability. In this work, we present INTVD with the philosophy of using Artificial Intelligence (AI) to detect vulnerabilities, while using Intelligence Assistant (IA) via providing interpretations for VD to support developers in further investigation. The interpretations include the sub-graph in the PDG of the given code including crucial statements, and variables with program slices, and the Common Weakness Enumeration (CWE) that are relevant to the detected vulnerability. First, we model the VD via Graph Convolution Network (GCN) with feature-attention (FA) mechanism. With the decision and the trained FA-GCN model, we develop a graph-based interpretation model via GNNExplainer with the formulation of finding the minimal PDG sub-graph and the minimal set of features that minimizes the prediction scores between using the entire graph or entire set of features and the minimal ones. Our empirical evaluation on a vulnerability database shows that INTVD is able to produce the interpretation on the vulnerable statements and crucial variables in 73.8% and 76.2% of the cases. It also reduces 80% of the numbers of statements that need to be investigated.

----------
# This repository is still under clearing and re-formating. 

# The Dataset we used in the paper

A c/c++ code vulnerability dataset with code changes and cve summaries: 

https://github.com/ZeoVan/MSR_20_Code_Vulnerability_CSV_Dataset

----------

# The Code for this paper:

https://github.com/interpretation2021icse/Interpretation-2021-ICSE/IntVD

