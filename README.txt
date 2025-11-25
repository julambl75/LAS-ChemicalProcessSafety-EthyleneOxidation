# Data

The data/ folder contains three files:
- component_order.csv: used by T_static to determine upstream components
- static.csv: data for T_static, to be split into train and validation
- dynamic.csv: data for T_dynamic, to be split into train and validation

# Learned Rules

The learned_rules/ folder contains one subdirectory for the static rules learned over the entire set of failures and process parameters, and one subdirectory for the dynamic rules learned over the "real-world" parameters, for the three different sets of failures considered in Table 2.

# Confusion Matrices

The confusion_matrices/ folder contains one subdirectory for each of the subsets of experiments considered. In each one, we provide the confusion matrices for the baselines and for T_dynamic, along with a labels.txt file that contains the mapping from class indices to experiment labels.

# Explainability of Baselines

The decision_trees/ folder contains decision trees taken from trained instances of the two baselines that are inherently explainable: RandomForest and AdaBoost. By default the maximum depths for models' decision trees are respectively 15 and 4, which both yield similar results.

# Table 2

The table_2_short_names/ folder contains a README file explaining the short names of Table 2 in detail; these will also be clarified in the final paper.
