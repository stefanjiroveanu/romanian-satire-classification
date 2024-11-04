
# romanian-satire-classification

This is a git repo that tackles down Kaggle's [Nitro Language Processing - 3rd Edition - Satire](https://www.kaggle.com/competitions/nitro-language-processing-3/submissions) by Nitro NLP where students had to develop a Machine Learning which classifies between Satire and Non-Satire Romanian news articles.
## Architecture

For the architecure of this solution I've chosen [distilbert-romanian-cased](https://huggingface.co/racai/distilbert-base-romanian-cased) and finetuned it. The current model scores 92-93% balanced-accuracy as per competition's rules.