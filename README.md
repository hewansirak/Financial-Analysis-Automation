How to leverage large language models (LLMs) to automate financial analysis. You will learn how to perform RAG over a financial dataset, use LLMs to generate financial reports, scrape websites, and extract sentiment from news articles. You will learn how to regenerate prompts, dynamically route models, and generate structured outputs.


### Requirements

Imagine you are working for a leading quantitative investment fund, Company X, that is looking to leverage LLMs to gain a competitive edge in stock selection. The company wants to build a system that can analyze vast amounts of textual data to identify promising investment opportunities before they become obvious to the market.

Pick 1 of the following 3 pathways to complete this project:

- **Research Automation:** Build a system that can find relevant stocks based on natural language queries from the user (e.g. "What are companies that build data centers?"). All stocks on the New York Stock Exchange must also be searchable by metrics such as Market Capitalization, Volume, Sector, and more.
- **Market Firehose:** Build a system that can handle 100 articles per minute. Your system should be able to process unstructured text articles and parse out the publisher, author, date, title, body, related sector. This should include an API and database schema. It must be a highly extensible system that can support articles from many different feeds, allows others to subscribe to the system to receive structured articles, and must operate as close to real time as possible while being able to handle processing hundreds of articles per minute.
- **Market Analysis:** Build a system that can process articles received from the market firehose.It should determine which companies are related to the article, a sentiment per company (positive or negative), and an event type classification for each article. Remember, this system must operate as close to real time as possible, and your system may receive hundreds of articles per minute.

### References

  - [What is Quantitative Analysis?](https://www.investopedia.com/articles/investing/041114/simple-overview-quantitative-analysis.asp)
  - [Text Classification with LLMs](https://hussainpoonawala.medium.com/text-classification-with-large-language-models-llms-a23c731a687e)
  - [Sentiment trading with Large Language Models](https://www.sciencedirect.com/science/article/pii/S1544612324002575)
  - [Stock Market Sentiment Prediction with OpenAI](https://www.insightbig.com/post/stock-market-sentiment-prediction-with-openai-and-python)
  - [Stock Market Data](https://www.sec.gov/data-research/sec-markets-data)
  - [Serving an LLM Application as an API Endpoint](https://www.datacamp.com/tutorial/serving-an-llm-application-as-an-api-endpoint-using-fastapi-in-python)
  - [Nasdaq Stock Screener](https://www.nasdaq.com/market-activity/stocks/screener)
  - [Accelerating LLM operations with parallel-parrot](https://bradito.me/blog/parallel-parrot/)
