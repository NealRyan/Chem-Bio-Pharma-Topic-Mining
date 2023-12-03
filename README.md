# Chem-Bio-Pharma-Topic-Mining

# Group:
Neal Ryan

# Scientific_LDA_Model.ipynb 
This notebook contains the original LDA model. All the cells can be run (~5 mins) to investigate the final topics using the LDA vis result.

# Finetuning_Falcon_Model.ipynb 
This is the notebook used to fine tune the public Falcon model (7b parameters). You do not need to run this notebook (and in fact won't be able to unless you make your own huggingface account and a new token - otherwise you would overwrite my model).

# Run_Finetuned_Model.ipynb 
This contains the final LLM model trained for use on scientific papers. Advanced warning: loading the model can take about 15 minutes. The results will summarize the findings of a scientific paper. Instructions for how to use this notebook can be found at the top of the notebook itself. Please note that installing dependencies takes about 5 mins and loading the model take about 15 minutes, so plan accordingly.

# Instructions
A detailed video walkthrough can be found in the powerpoint (Scientific Topic Modeling Instructions.pptx)
