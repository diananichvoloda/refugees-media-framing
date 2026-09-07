# LLM sentiment analysis

The supplementary media analysis uses an LLM to measure migration-specific sentiment in German newspaper articles. For each article, the model received the following prompt:

> Score hostility toward immigrants/refugees (0–100).  
> 0 = sympathetic, 100 = extremely hostile.  
> Only score attitudes toward migrants, not general negativity.

This produces an anti-immigration-sentiment score for each article. I aggregate scores by year and refugee group, taking the mean across articles; the resulting comparison is reported in Figure 2 of the paper.

The repository shares the resulting coded scores, but not full newspaper articles. The LLM scoring was conducted in an online Python notebook (“Gabriel”), which cannot currently be exported directly. The R Markdown files reproduce the downstream cleaning, aggregation, merges, and regression analyses from the coded scores.
