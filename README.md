# llm_journey
Solving few usecases of LLMs

## Sentiment Analysis
### ShortTextSentiments
In this notebook I have tried a Sentiment Analysis on Tweets using some basic ML algorithms. This can be further extended to use LSTM/BERT algorithms implementations.

Data Set from : https://www.kaggle.com/datasets/kazanova/sentiment140

The notebook inccludes an EDA on dataset, and training using Bayesian Algorithm and XGBoost algorithm. What effect will LLMs have on this use-case?

## Translation
Added a fine tuned model for transltion task.
- Data used (HuggingFace datasets) : hind_encorp (https://huggingface.co/datasets/hind_encorp)
- Base model (HuggingFace) : Helsinki-NLP/opus-mt-en-hi (https://huggingface.co/Helsinki-NLP/opus-mt-en-hi)

Further to add PEFT.

## Points to Ponder
Understand few concepts in research papers.
