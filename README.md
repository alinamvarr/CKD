# Chronic Kidney Disease (CKD) Dataset Analysis

This repository contains an analysis of the **Chronic Kidney Disease (CKD)** dataset using **Elastic Principal Graphs** with the **ClinTrajan** package.

## Dataset

The CKD dataset used in this analysis is publicly available on Kaggle:

- [Chronic Kidney Disease Dataset](https://www.kaggle.com/datasets/rabieelkharoua/chronic-kidney-disease-dataset-analysis/)

Please download the dataset from the Kaggle link above and place it in the appropriate directory (you can specify the folder name here).

## Analysis Overview

We use **Elastic Principal Graphs** to analyze the CKD dataset and focus on creating and interpreting **pseudotime trajectories** . The main aim of the analysis is to explore disease progression insights using these methods.

## Tools and Libraries

The analysis is performed using the **ClinTrajan** package. You can find more information about ClinTrajan at the following link:

- [ClinTrajan GitHub Repository](https://github.com/auranic/ClinTrajan)

## Results 
1. **Principal Tree Example with Different Variables**: 
   
   The figure below displays the principal tree structure, where different branches represent various patient subgroups. Each plot illustrates how a specific clinical variable (e.g., serum creatinine, GFR, sodium levels) varies across the branches, highlighting differences in CKD progression within the dataset.

![CKD Principal Tree](./image/principal_tree_visexamples_CKD.png)
