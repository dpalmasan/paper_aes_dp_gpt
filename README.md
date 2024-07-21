# An LLM-based Hybrid Approach for Enhanced Automated Essay Scoring: Leveraging Linguistic Features for Coherence and Quality Assessment

## What is this repo

This repo contains the source code (jupyter notebooks) of the paper approach. Note that we cannot distribute the data, but it is available for download once the user fills the terms of agreement. The data is from the competition [The Hewlett Foundation: Automated Essay Scoring](https://www.kaggle.com/competitions/asap-aes/code). The notebooks assume that you have the data downloaded and it loads the `.tsv` version of it. The notebooks assume as well that you will have the data in the current directory, so data will be under `"./training_set_rel3.tsv"`.

We are also using GPT-4 for some experiments and OpenAI embeddings. To run those you will need to have access to Open AI API keys. We assume that the key will be in an environment variable `OPEN_AI_API_KEY`. We do not provide any API KEY.

## Generating Sentence Embeddings

To get the essays embeddings and the sentence embeddings, we pre-computed them in a separate notebook as embedding computation is expensive. This pre-computation of embeddings happens in the file `AES + GPT paper Pre-Compute Embeddings.ipynb`.