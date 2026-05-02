# shein-sustanability-twitter-analysis
## Overview
Queried Twitter API across 4 keyword categories (sustainability, greenwashing, fast fashion, @SHEIN_Official) spanning 2020–2023; built time series visualizations, sentiment analysis dashboards, and word clouds to surface dominant narratives around Shein's environmental practices. With the growth of fashion consumerism, the debate on sustainability in the fashion world has been in the global spotlight. One of the main subjects has been the clothing company
SHEIN. Intertwined with discussions regarding cheap prices, clothing pollution, stealing designs
of small businesses, working conditions, and quality, SHEIN has been highly criticized for their
connections to sustainability (or lack thereof). With their labeling as a “fast fashion” brand,
SHEIN has been under fire for their overproduction, especially from the Twitter community. In
response, SHEIN started promoting campaigns about their “sustainability practices” which
further put them under more criticism for greenwashing, a term used to describe promoting
surface-level sustainability practices that are untrue, misleading, or ineffective. SHEIN’s major
role in the sustainable clothing debate has been a subject of interest of mine.

## Queries
1. Shein sustainability/sustainable
2. Shein greenwashing
3. Shein fast fashion
4. @SHEIN_Official

## Methodology
- Queried the Twitter API to collect tweets excluding retweets across all four categories
- Built time series visualizations to track tweet volume over time and identify spikes in public discourse
- Ran sentiment analysis on @SHEIN_Official tweets to track how public perception of Shein's own account shifted
- Generated word clouds from tweet text to surface dominant narratives and recurring themes within each category

## Visualizations
![Shein Sustainability Tweet Counts](images/sustainability_tweet_counts.png)
![Shein Fast Fashion Tweet Counts](images/fast_fashion_tweet_counts.png)
![Shein Greenwashing Tweet Counts](images/greenwashing_tweet_counts.png)
![Shein Fast Fashion Word Cloud](images/fast_fashion_wordcloud.png)
![Shein Greenwashing Word Cloud](images/greenwashing_wordcloud.png)
![Shein Sustainability Word Cloud](images/sustainability_wordcloud.png)
![SHEIN_Official Sentiment Analysis](images/sentiment_analysis1.png)
![SHEIN_Official Sentiment Analysis](images/sentiment_analysis2.png)


## Key Findings
- Spikes in "fast fashion" discourse dwarfed "greenwashing" and "sustainability" mentions, suggesting mainstream conversation rarely uses technical sustainability language
- "Greenwashing" discourse emerged significantly later (2022) compared to fast fashion criticism, coinciding with increased media coverage
- @SHEIN_Official sentiment dropped sharply in early 2023, correlating with increased scrutiny of the brand's practices

## Tools & Libraries
- Python
- Twitter API v2
- matplotlib
- wordcloud
- Pandas

