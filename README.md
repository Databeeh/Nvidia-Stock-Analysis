# NVIDIA Stock Analysis: Scandal Dip vs. AI Fundamentals

A beginner-friendly Python project that analyzes NVIDIA stock around a recent CEO-related news event. The goal is to separate short-term sentiment-driven volatility from long-term value. 

# The question

Does a short-term scandal-driven dip change NVIDIA's long-term value?

# My argument

No. NVIDIA's stock price may fall on news-driven selling, but the company's real value is built on:

GPU dominance in AI: NVIDIA's graphics processing units, or GPUs, are the chips that train and run most modern AI models.
The CUDA ecosystem: CUDA is NVIDIA's toolkit that lets developers use those GPUs for general computing. Turning NVIDIA into a general-purpose AI company. 

Sustained AI infrastructure demand: Cloud providers and enterprises are still spending heavily on AI hardware. Infrastructure spend is likely to keep growing, driven by the big hyperscalers.
The dip is a sentiment event. The fundamentals are still intact. 

# Tools used

Google Colab
yfinance
pandas
plotly

# What the chart shows

The notebook downloads one year of NVIDIA stock data and plots:

Closing price

50-day and 200-day simple moving averages

A vertical marker for the date the CEO-related news broke

Trading volume below the price chart

The moving averages help smooth out daily noise so the longer-term trend is easier to see. High volume around the dip suggests news-driven selling rather than a slow business decline.

# How to run

Click the Open in Colab badge at the top of the notebook and run the cells from top to bottom.

# Data source

Yahoo Finance via the yfinance Python library.

# Key takeaway

Short-term headlines can move a stock. Long-term value comes from what a company actually builds and sells. NVIDIA's GPUs and AI infrastructure demand are the real story.



