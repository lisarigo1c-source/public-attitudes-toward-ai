# Public-attitudes-toward-ai
Exploring public attitudes toward artificial intelligence through Reddit discussions and New York Times articles using R, sentiment analysis and topic modelling.
# Exploring Public Attitudes Toward Artificial Intelligence

**Academic group project | Web & Social Mining · Text Analytics · NLP**

**Tools:** R, RSelenium  
**Methods:** Web scraping, text preprocessing, sentiment analysis, TF-IDF, hierarchical clustering, semantic networks and topic modelling

## Project Overview

This academic project explores how artificial intelligence is discussed in **online communities and news coverage**, using two complementary text sources: Reddit discussions and New York Times articles.

The analysis combines data collection, text cleaning, descriptive analysis and natural language processing to investigate recurring themes, sentiment and the structure of AI-related discourse.

## Data Sources and Analysis

### Reddit Discussions

- Collected AI-related discussions, including threads and comments, using R-based scraping tools.
- Retained text and contextual metadata such as post/comment dates and engagement information.
- Applied language filtering, text cleaning and rules to identify AI-related opinion content.
- Explored discussion activity and emotional or sentiment patterns.

### New York Times Articles

- Analysed **535 AI-related articles** published between **January 2023 and November 2025**, drawn from 25 newspaper sections.
- Created textual inputs from article titles and abstracts, then applied cleaning, tokenisation and lemmatisation.
- Explored important terms with **TF-IDF**, as well as hierarchical term clusters and semantic co-occurrence networks.
- Compared topic modelling approaches to identify recurring themes in news coverage.

## Topic Modelling

Four approaches were compared on the newspaper corpus:

- **Latent Semantic Analysis (LSA)**
- **Non-negative Matrix Factorisation (NMF)**
- **Latent Dirichlet Allocation (LDA)**
- **Biterm Topic Model (BTM)**

Using the project's *mean log-ratio topic coherence* comparison, **LSA achieved the strongest average coherence** of the four approaches considered. The selected LSA solution highlighted themes including digital infrastructure, finance, technology companies, education, governance and international competition.

These findings describe the analysed sample and the evaluation criterion used; they are not a representative measurement of public opinion as a whole.

## Repository Contents

- [analysis/](analysis/) — R scripts for scraping, preprocessing and text analysis.
- [presentation/](presentation/) — Project presentation materials.
- [data/](data/) — Documentation of the data sources and collection approach.



## Academic Context

Group project for *Web and Social Mining*, University of Bologna.  
**Authors:** Abir Abamadiane, Paola D'Amore and Lisa Rigo  
