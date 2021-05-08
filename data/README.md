## Data files for COMM313 Final Project

Welcome to my data folder! 

This is my data hub, containing ALL the data files utilized in creating my final story. My data folder is organized as follows. The first file is the composite.zip file which is a zip folder obtained from my Lexis Nexis bulk data download. 

The text folder contains the output files from my data_prep step. The text folder is organized into 5 separate subfolders, one for each publication news source (China Daily, NY Times, Daily Telegraph, Guardian, and Hindustan Times). Each source subfolder contains each article published by that source in my corpus as a txt file and the file name begins with the source name. There is also a composite_text.txt in each subfolder that essentially has all of the body text from all of the articles for that source in one file. The terms_only_texts.txt in each subfolder resulted from a subunit analysis during my data analysis. Finally there is a source specific corpus_index.json file that logs all the files. This is described in detail below.

There is an all_corpus_index.json file that logs all the files for all five sources.

There is a china_daily_second_sample.RTF file that contains the articles of my second Lexis Nexis manual sample download of articles that were missing from my initial bulk data download.

### Data:

All my data was downloaded from Lexis Nexis. The bulk data download was through the Penn server with search terms COVID-19 and origins, all publications post 01/01/2019 to end of March 2021, in English. Only publications from the 5 selected sources were included ((China Daily, NY Times, Daily Telegraph, Guardian, and Hindustan Times)).

The second data download was not a bulk download but manual download from Lexis Nexis using the same search queries but only from the China Daily and excluding the sources already included from the bulk download.

For my initial personal research, I included links to some fun articles to read about some conspiracy theories.

### text subfolder:

**The text subfolder is further organized into 5 separate folders.**

**Due to the quantity of files in each subfolder, I have not listed every single file name (txt file), but have included identifying information including # of files and what the file name startes with. All file names start with indicator of the source**

- `china_daily`: contains articles by China Daily from bulk data download. There are 319 txt files in total within this folder for articles. There is one cd_composite_text.txt file, one cd_terms_only.txt file, and a corpus index specific to the China Daily.
- `daily_telegraph`: contains articles by Daily Telegraph from bulk data download. There are 415 txt files in total within this folder for articles. There is one dt_composite_text.txt file, one dt_terms_only_txt file, and a corpus index specific to the Daily Telegraph.
- `guardian`: contains articles by the Guardian from bulk data download. There are 952 txt files in total within this folder for articles. There is one composite text txt file, one terms only txt file, and a corpus index specific to the Guardian.
- `hindustan times`: contains articles by Hindustan Times from bulk data download. There are 655 txt files in total within this folder for articles. There is one ht_composite_text.txt file, one ht_terms_only.txt file, and a corpus index specific to the Hindustan Times.
- `nyt`: contains articles by NY Times from bulk data download. There are 549 txt files in total within this folder for articles. There is one nyt_composite_text.txt file, one nyt_terms_only.txt file, and a corpus index specific to the NY Times.



Sources: 

Nexis Uni, Lexis Nexis: https://www.lexisnexis.com/en-us/professional/academic/nexis-uni.page


Additional references for information about COVID-19 conspiracy theories and timelines:

- Lab-Leak Theory: Brewster, J. (2020, May 24). A Timeline Of The COVID-19 Wuhan Lab Origin Theory. Forbes. https://www.forbes.com/sites/jackbrewster/2020/05/10/a-timeline-of-the-covid-19-wuhan-lab-origin-theory/?sh=221fd9115aba.

- Biowarfare Theories: Nie J. B. (2020). In the Shadow of Biological Warfare: Conspiracy Theories on the Origins of COVID-19 and Enhancing Global Governance of Biosafety as a Matter of Urgency. Journal of bioethical inquiry, 17(4), 567–574. https://doi.org/10.1007/s11673-020-10025-8

- Cold-chain Theory: Lewis, D. (2021, February 26). Can COVID spread from frozen wildlife? Scientists probe pandemic origins. Nature News. https://www.nature.com/articles/d41586-021-00495-0.

- General Overviews: David Klepper, F. A. (2021, February 15). The superspreaders behind top COVID-19 conspiracy theories. AP NEWS. https://apnews.com/article/conspiracy-theories-iran-only-on-ap-media-misinformation-bfca6d5b236a29d61c4dd38702495ffe.
 



    