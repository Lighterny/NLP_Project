# NLP_Project

### Folders/Content:
* NLP_Project (Home)
  * NLP
     * RecommEng
       * **_NLP_RecommEng.ipynb_** --> Jupyter Notebook showing text analytics (NLP preprocessing, LDA topic modelling, etc.) + recommender engine designs
       * **_NLP_Repord.pdf_** --> Report explaining rationale and results of recommender engines explored. 
     * Web Scraping 
       * **_Selenium_Webscrape.pdf_** --> Report explaining rationale for scraping White House Press Briefings + webscraper design spec. 
       * **_Selenium_Webscrape.ipynb_** --> Jupyter Notebook for webscraper design
       * **_white_house_news.xlsx_** --> Text Data Webscraped from White House Press Briefings

### Recommender Engines Folder
I designed and assessed the efficacy of two types of recommender engines (collaborative filtering (CF) and content-based). Of each type, I explored three variations to see which would best recommend university courses and reading titles. To do this, NLP techniques were applied, including stop-word removal, stemming, lemmatisation, and n-gram dependency grammar, and topic modelling using Latent Dirichlet Allocation (LDA). The recommender systems were quantitatively assessed using descriptive statistics of recommendations' cosine similarity scores above a 0.4 threshold. 

### Web Scraping Folder
A selenium webdriver was designed to scrape text from the official US White House Press Briefings website. This was motivated to conduct future text analytics and/or topic modelling that could serve to evaluate the administrations' priorities and agenda. 
