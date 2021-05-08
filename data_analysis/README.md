## Data analysis notebooks for COMM313 Final Project

Welcome to my data analysis folder!

There are three types of data analysis notebooks in this folder:
1) Exploration notebooks (titled "data_prep"): in this notebook, I import the raw zip files and second China Daily sample, do some initial cleaning, and then export into the appropriate data text subfolders. I also organize into further layers of subfolders here as well. 
2) Analysis notebooks (titled by source- 5 total): in these analysis notebooks, I import the cleaned texts relevant to analysis, conduct analysis on available data and make observations throughout.  This is the crux of my analysis! I include concise observations that extract the key points that jumped out to me while I was conducting the analysis.
3) Comparative analysis notebooks (contains 'comparative_analysis' in title): these notebooks contain attempts to directly compare the five sources to each other rather than independent investigations.

**Notebooks list:**

There's first a functions notebook with all relevant functions.
There's also some loaded NRC Lexicon files used in sentiment analysis.

Exploration:
   - `data_prep`: This notebook contains preliminary cleaning, organizing, and exporting of txt files from each source. This is where I discovered I needed additional data for my China Daily corpus.

   
Analysis Notebooks:

   - `china_daily`: This notebook was analyzing frequencies, KWIC, etc for China Daily texts. Goes through entire process of tokenizing and whatnot.
   - `new_york_times`: This notebook was analyzing frequencies, KWIC, etc for NY Times texts. Goes through entire process of tokenizing and whatnot.
   - `the_daily_telegraph`: This notebook was analyzing frequencies, KWIC, etc for Daily Telegraph texts. Goes through entire process of tokenizing and whatnot. 
   - `the_guardian`: This notebook was analyzing frequencies, KWIC, etc for Guardian texts. Goes through entire process of tokenizing and whatnot.
   - `hindustan_times`: This notebook was analyzing frequencies, KWIC, etc for Hindustan Times texts. Goes through entire process of tokenizing and whatnot.
   
Comparative Analysis Notebooks:

   - `time_comparative_analysis`: This notebook contained comparison by publication time for the five sources.
   - `comparative_analysis_frequency_keyness`: This notebook contained comparison of five texts for frequency lists and keyness.
   - `comparative_analysis_targeted_sentiment`: This notebook contained comparison for sentiment related analyses.
   - `comparative_analysis_doc_term_matrix`: This notebook contained comparison for Doc Term Matrix differences.
   
