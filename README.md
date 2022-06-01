# Model

## 1. Doc2Vec
We imply Doc2Vec method to learn paragraph and document embeddings via the distributed memory and distributed bag of words models.

For a usage example, see the: https://radimrehurek.com/gensim/auto_examples/tutorials/run_doc2vec_lee.html#sphx-glr-auto-examples-tutorials-run-doc2vec-lee-py.

### Status:
* May 19: 
  - Try model on simple paragraph. No error was occurred
  - Still need to tune for hyperparameters and run evaluation, but need more doc 

## 2. Text Classification:
The dataset for fine-tuning is the [Financial Phrase Bank Dataset](https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10) that was collected by [Maloet al, 2014](https://arxiv.org/abs/1307.5336) 

### Some of the papers that might be useful

1. Predicting Market-Volatility from
Federal Reserve Board Meeting Minutes
NLP for Finance  
http://web.stanford.edu/~rezab/papers/finlpreport.pdf

2. Classification of "Hot News" for Financial Forecast Using NLP Techniques  
https://ieeexplore.ieee.org/abstract/document/8621903

3. Attention-based Stock Price Movement Prediction Using 8-K Filings  
https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/reports/custom/15751328.pdf

4. Twitter mood predicts the stock market  
https://arxiv.org/abs/1010.3003

5. Natural language based financial forecasting: a survey  
https://www.proquest.com/docview/1965735376?accountid=14510&pq-origsite=summon

6. The predictive power of public Twitter sentiment for forecasting cryptocurrency prices  
https://www.sciencedirect.com/science/article/pii/S104244312030072X?via%3Dihub

7. Predicting the Effects of News Sentiments on the Stock Market  
https://ieeexplore.ieee.org/abstract/document/8621884

8. Textual Sentiment in Finance: A Survey of Methods and Models  
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2213801

9. Are Investors Influenced By How Earnings Press Releases Are Written?  
https://journals.sagepub.com/doi/10.1177/0021943608319388

10. The effect of manager-specific optimism on the tone of earnings conference calls   
https://www.researchgate.net/publication/276477867_The_effect_of_manager-specific_optimism_on_the_tone_of_earnings_conference_calls

11. Earnings conference calls and stock returns: The incremental informativeness of textual tone  
 https://econpapers.repec.org/article/eeejbfina/v_3a36_3ay_3a2012_3ai_3a4_3ap_3a992-1011.htm
 
 
### GloVe: Global Vectors for Word Representation from Standford
https://nlp.stanford.edu/projects/glove/

https://github.com/stanfordnlp/GloVe
