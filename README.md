# openai-qn-answer
This repository uses openai apis to generate question and answers from a web or a file

# Some more changes for testing
We will be using openai apis to build a system that can answer questions about a website and a file

This repo is divided into 3 parts:

1. Web crawler
2. Create embeddings
3. Ask Questions 

## How to run
A. Web Crawler
1. pip install -r requirements.txt
2. Update domain and full url in web_crawl.py
3. Run python web_crawl.py

This will save crawled texts into text/ folder

B. Create Embeddings
1. Update domain and full url in embeddings.py
2. Run python embeddings.py

C. Ask Questions - This is final step after we have completed previous 2 steps
1. Update the question in ask_question.py
2. Run python ask_question.py

```
### My tasks
- [ ] Take domain and full url from arguement
- [ ] Input questions from argument
- [ ] Create basic UI for the above
```



