---
title: "Understanding Tourist Perceptions of Urban Waterfronts"
thumbnail: /assets/img/tourist-waterfronts.png
layout: project
permalink: /projects/tourist-waterfronts/
selected: y
category: cultural-tourism-research
---
### 1. Research Questions
* How do international tourists perceive waterfront spaces, and what are the specific differences in perception between the Huangpu River and the Suzhou River?
* How can crowdsourced online travel reviews support evidence-based urban planning and design decisions?

### 2. Data Source
**Data Origin:** Online travel reviews scraped from TripAdvisor (covering review contents, country of origin, date of visit, travel type, and ratings).
<img src="/assets/NLP_1.png" class="u-max-full-width" alt="Space Syntax-Based Accessibility Analysis of the Pearl River Delta">

**Study Area:** The Huangpu River corridor and Suzhou River waterfronts in Shanghai, China.

### 3. Research Route & Methodology
**Data Processing Pipeline:** Web Scraping (using `DrissionPage` and `lxml`) $\rightarrow$ Translation to Chinese (`DeepL API`, `deep-translator`) $\rightarrow$ Text Cleaning & Segmentation (`jieba`, stopword filtering) $\rightarrow$ Word Frequency Analysis & Word Clouds (`matplotlib`, `wordcloud`) $\rightarrow$ Sentiment Analysis (`tencentcloud.nlp`) $\rightarrow$ Topic Modeling (`gensim` LDA) $\rightarrow$ Keyword Co-occurrence Network Analysis (`pyvis.network`).

### 4. Key Results & Insights
**Perception Differences:**
  **Huangpu River:** Mainly visited by high-spending tourist groups (couples and families). Perceived as an iconic landmark representing Shanghai's modern skyline, light shows, economic prosperity, and urban modernization. Visitors predominantly experience it via night cruise ships. Negative reviews center around river water quality, overcrowding, public safety disorder, and cold climate during winter.<br>
  **Suzhou River:** Primarily attracts explorative visitors (solo travelers). Viewed as a venue to experience the city's historical, cultural, and local identity. Visitors prefer strolling or cycling along the riverfront promenades. Negative feedback relates to localized water pollution and a limited variety of recreational activities.
<img src="/assets/NLP_3.png" class="u-max-full-width" alt="Space Syntax-Based Accessibility Analysis of the Pearl River Delta">
<img src="/assets/NLP_4.png" class="u-max-full-width" alt="Space Syntax-Based Accessibility Analysis of the Pearl River Delta">
