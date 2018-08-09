# Identify trends, innovations, treatments and sentiments associated with them for Parkinson’s or any other disease using Method DS Method
## Get Data
 * Collect research details of a particular disease using PubMed Entrez or PubMed API
 * Using esearch and efetch e-utilities, extract data in JSON format by specifying db, Retmode, term and Retmax 
## Exploratory Data Analysis is performed using Pandas.
### Modeling Frequency distribution and weight of words in abstracts:
* WordNetLemmatizer along with FreqDist 
* SnowballStemmer is used along with CountVectorizer. 
* Abstracts are transformed into bag of words representation and Tf-idf weights are calculated using Tfidftransformer
* Compared results for FreqDist and CountVectorizer

### Sentiment Analysis
* Sentiment analysis is performed using SentimentIntensityAnalyzer. Compound score is used to assign positive or negative sentiment to the article
* Cloud of words is also modelled using positive and negative scores calculated for the article

  
 
