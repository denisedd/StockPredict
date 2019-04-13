# StockPredict
CMPT 733 Final Project

1. Code/1DataCollection&Preprocess
AllSymbolScraper.py -- scrape all nasdaq company name and stock symbol.
ExtractNYTNews.py -- parse HTML files and store to json.
Text_Preprocessing.ipynb -- prepross Json files and store to pickle file.
stockDataGetter.ipynb -- get company stock price and nasdaq index.
Twitter_api.py -- for extracting twitter data from api (reference : https://github.com/tweepy/tweepy)
Twitter_parse.py & Twitter_reformat.py -- for twitter data cleaning and preprocessing

2. Code/2DataAnalysis
TopicModeling -- train lda model and visualize result.
wordcloud.py - for twitter data visualation.

3. Code/3ModelDevelopment
Doc2Vec -- Doc2Vec model development and LSTM model for binary prediction
base_model_nasdaq.ipynb -- baseline model for logistic regression and linear regression

For large files download from Google Drive:
1. Code/3ModelDevelopment/Doc2Vec/doc2vec_model.docvecs.vectors_docs.npy 
https://drive.google.com/open?id=1XhfAJkx6Ign9AMc5eHe3pp_cg5W5YSmg

2. Data/ProcessedNews.pkl
https://drive.google.com/open?id=1hMsiEZoP5ITTy7B-5fr_NH0W4Vb46YQu
