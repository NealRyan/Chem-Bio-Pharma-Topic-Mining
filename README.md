# Chem-Bio-Pharma-Topic-Mining

Scientific_LDA_Model.ipynb contains the original LDA model. All the cells can be run (~5 mins) to investigate the final topics using the LDA vis result.

Finetuning_Falcon_Model.ipynb is the notebook used to fine tune the public Falcon model (7b parameters). You do not need to run this notebook.

Run_Finetuned_Model.ipynb contains the final LLM model trained for use on scientific papers. The results will sumarize the findings of a scientific paper. Instructions for how to use this notebook can be found at the top of the notebook itself. Please note that installing dependencies takes about 5 mins and loading the model take about 15 minutes, so plan accordingly.
