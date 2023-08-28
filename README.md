# Llama2-Chainlit-Chatbot
This is a Llama2 chainlit chatbot. With ingest trained on medical pdf file. This is bot built using Llama2 and Sentence Transformers. The bot is powered by Langchain and Chainlit. 
The bot runs on a decent CPU machine with a minimum of 16GB of RAM.

There are only two chnages done
1) Project is almost same as original only additional detail is addition of ipunb file to run it on Google colab
2) Download directly the llama-2-7b-chat from huggingface directly instead of manually downloading the model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ndn1954/Llama2-Chainlit-Chatbot/blob/main/Chainlist_llama2.ipynb)

## Installation

```bash
pip install -r requrements.txt
```
## Prereq
Run Ingest to load the pdf file
```bash
python ingest.py
```

## Start with Chainlit to start chatbot

```bash
chainlit run model.py -w
```
## Performance

Bot will be slow as it is running on CPU each question takes around 3-5 mins
