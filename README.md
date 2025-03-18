# Toolformer Training Pipeline for Web Search

This repository contains a training pipeline for fine-tuning Llama 3.2 1B model with Toolformer ([arXiv:2302.04761](https://arxiv.org/abs/2302.04761)) approach. We train the model specifically for web search capabilities by using duckduckgo_search as our API to make websearch queries.

## Overview

The entirety of the code is contained in project.ipynb. 
The rest of the files in the repositories consits of logs/results/model_weights and dumps of the train_set after certain processing steps.

The code in the jupyter notebook is structured in 5 main parts: 

I/ Sampling API calls 
II/ Executing API calls
III/ Filtering useless or harmful API calls/
IV/ Finetuning on the filtered dataset
V/ Results 