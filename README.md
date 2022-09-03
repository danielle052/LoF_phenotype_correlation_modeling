# LoF-modeling
This repository contains:
1) LoF_preprocess.py- the script that creates the data for LoF visualizations.
2) LoF_tool_statistical_validation.py- in this script, we test if LoF relative positions on the gene correlate with phenotypes.
3) LoF_visualization.py- visualizes different LoF variants.
4) gene_parser.py- creates a dictionary of all genes associated with a specific disease according to PWAS.
5) README


How to get visualization and statistical analysis of the relationship between phenotypes and LoF mutations' relative position:
1) Clone this repository
2) Run create_visualization_data(phenotype_name, isICD10, PHENOTYPE, phen_threshold, dir_output_path, genes_path, gene_fdr_col, gene_fdr_thershold, firm_threshold=0.2)    from LoF_preprocess.py with the relevant parameters according to the function ducmentation.
3) Run run_program(pathologies_list, folder_path) from LoF_visualization.py. make sure that the folder_path is the same as dir_output_path.
4) For statisiacal tests use LoF_tool_statistical_validation.py with the relevant function.

