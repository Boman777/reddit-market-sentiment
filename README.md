# reddit-market-sentiment

# Reddit Market Sentiment

A read-only Reddit sentiment analysis tool for finance-related communities.

## Overview

This project uses Reddit's official API to read publicly available posts and comments from selected finance-related subreddits, then performs basic sentiment analysis in Python.

It is designed for:
- market sentiment research
- earnings discussion monitoring
- topic trend detection
- public community signal analysis

## Scope

This app is strictly **read-only**.

It does **not**:
- post submissions
- write comments
- send messages
- vote on content
- moderate communities
- interact with users

## Example Use Cases

- Track sentiment around earnings releases
- Compare discussion tone across subreddits
- Monitor bullish vs bearish language for specific tickers
- Build a simple sentiment dashboard for research

## Target Subreddits

Examples:
- `r/stocks`
- `r/investing`
- `r/wallstreetbets`

## Tech Stack

- Python 3.10+
- PRAW
- TextBlob
- python-dotenv

## Setup

### 1. Clone the repo

```bash
git clone https://github.com/yourname/reddit-market-sentiment.git
cd reddit-market-sentiment
