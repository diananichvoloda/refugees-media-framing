# Data guide

This repository contains the code and shareable derived data used in the paper, “Refugees, Media Framing, and the Rise of the Far Right in Germany.”

## Derived data

The `derived/` folder will contain the final analysis-ready datasets used by the R Markdown files:

- `iv_total_new.csv`: district-level panel combining refugee exposure, election outcomes, and control variables.
- `article_sentiment_scores.csv`: LLM-generated migration-specific sentiment scores for the newspaper-article sample. This file excludes full article text.
- `speech_sentiment_scores.csv`: LLM-generated migration-specific sentiment scores for the parliamentary-speech sample. This file excludes full speech text.

## Raw data sources

Raw inputs were drawn from public German statistical and election sources, including Destatis GENESIS, German federal and European election returns, and public state-parliament records.

Some raw newspaper and speech text is not redistributed here. The repository instead provides the resulting coded sentiment data and documents the analysis workflow.
