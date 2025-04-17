📝 BusinessDay Nigeria Economy Article Analysis
Goal: Scrape, process, and analyze news articles from the Economy section of BusinessDay Nigeria to uncover sentiment trends, key themes, and editorial patterns.
________________________________________
🔧 Tools Used
•	Scraping: Octoparse, requests, BeautifulSoup
•	Analysis: pandas, nltk, rake-nltk, matplotlib, seaborn
•	Sentiment Scoring: VADER (NLTK)
•	Keyword Extraction: RAKE
________________________________________
🔍 Methodology
1.	Scraped 5904 article URLs using Octoparse.
2.	Extracted article details (title, date, author, content) via Python.
3.	Analyzed sentiment (positive, neutral, negative) with polarity scores.
4.	Preprocessed text for cleaner keyword extraction and sentiment comparison.
5.	Visualized trends using pie charts, line plots, and more.
________________________________________
📊 Key Insights
•	Majority of articles were positive in tone, especially around FX and investment topics.
•	Polarity scores remained consistently high, indicating optimistic reporting.
•	Top keywords included: CBN, inflation, foreign exchange, investment.
•	Recurring contributors suggest editorial consistency and focus.
________________________________________
⚠️ Challenges & Fixes
•	Bypassed 403 errors User-agent spoofing and octoparse fixed this error.
•	Handled missing fields, noisy keywords, and inconsistent date formats.
•	Compared raw vs cleaned sentiment for accuracy trade-offs.
________________________________________
📁 Deliverables
•	updated_scraped.csv: Full dataset with sentiment, polarity, and keywords
•	SCRAPED.ipynb: End-to-end analysis notebook
•	requirements.txt: Project dependencies
•	BusinessDay_Economy_Report.pdf: Full written report
•	octoparse.img: Screenshot of Octoparse workflow
________________________________________
✅ Conclusion
A complete NLP pipeline combining no-code tools and Python automation to monitor media sentiment and extract economic insights from Nigerian news.


