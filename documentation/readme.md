This is documentation for the Chatbot feature inside *OpenFinAL*. This document will talk about features, ideas, and chat conversations. 
## Table of Contents
- [Introduction](#Introduction)
- [Chatbot Features](https://github.com/Cipher-gg/OpenFinAL-Fork/blob/main/documentation/readme.md#chatbot-features)
- [Chatbot Ideas](https://github.com/Cipher-gg/OpenFinAL-Fork/blob/main/documentation/readme.md#chatbot-ideas)
- [Chatbot Conversations](https://github.com/Cipher-gg/OpenFinAL-Fork/blob/main/documentation/readme.md#topics-chatbot-can-converse-about)

## Introduction
The current build of the Chatbot is using OpenAI's ChatGPT-4. This is being done via API keys. Stonky is an advanced financial advisory chatbot designed to provide personalized investment assistance to users of all experience levels. Unlike traditional financial chatbots, Stonky will adapt to each user's knowledge level, offering explanations that are tailored to their understanding; from the basic concepts for beginners to experienced traders. 
## Chatbot Features
### Learning & Response System
- Automatically gauges users experience level through the initial onboarding 
- Adjusts explanation complexity based on a user's financial knowledge. 
- Allows for manual override with "Change my level" option.
- Provides a straight to the point explanation for beginner s and detailed analysis for experts. 
### Knowledge Base
- **Investment Fundamentals**: Covers basic terms (stocks, bonds, dividends, portfolios, etc.)
- **Technical Analysis**: Explains P/E ratios, EPS, candlestick charts, trading volumes
### User Interface
- Sidebar Icon and expandable pop-ip chat window
- Animated mascot compacted system status
## Chatbot Ideas
- Have the ability to reference past conversations.
## Chatbot Conversations
*Mock Up Example*

[Chat Example](https://github.com/user-attachments/files/19668771/MK1.Chatbot.design.pdf)


### Chatbot Introduction Prompt
**First Time User Detection**
Hi I’m Stonky, your personal investing assistant. Are you new to investing, 
Chat bot will ask user what experience level of investor they are
- [Novice](https://github.com/Cipher-gg/OpenFinAL-Fork/blob/main/documentation/readme.md#novice)
- [Intermediate](https://github.com/Cipher-gg/OpenFinAL-Fork/blob/main/documentation/readme.md#intermediate)
- [Advanced](https://github.com/Cipher-gg/OpenFinAL-Fork/blob/main/documentation/readme.md#advanced)
#### Novice 
"Are you new to financial analytics? I can walk you through the basics or help you dive into some data. What would you like to start with?"  

"Would you like to analyze a stock, explore an investment strategy, or just learn some finance fundamentals?"  

"Let’s get you started! You can type things like: ‘Show me the latest trends in tech stocks’ or ‘Explain P/E ratios.’ What would you like to do?"

#### Intermediate 
"Looking for insights? I can analyze stock performance, compare sectors, or highlight market movers. What’s on your radar?"

"Markets can be unpredictable, but data helps. Want to explore volatility, correlations, or backtest a strategy?"

"How do macroeconomic factors affect your portfolio? Let’s explore interest rates, inflation, and GDP impacts."

"Are you tracking any stocks? I can fetch recent price movements, earnings reports, or sentiment analysis."

"Considering a new investment strategy? I can help analyze past performance, run simulations, and evaluate risks."

#### Advanced 
"Want to stress-test your portfolio? Let’s explore risk metrics, beta analysis, and hedging strategies."

"Exploring options strategies? I can model Greeks, implied volatility skews, and options pricing scenarios."

### Topics Chatbot Can Converse About
#### Definitions
- Basic Investment terms
	- Stock, Bond, Mutual Fund, Index Fund, Portfolio
- Risk & Return terms
	- Risk, Return, Diversification, Volatility, Liquidity
- Stock Market terms
	- Bullish, Bearish, Market Cap, Dividend, Earnings per Share (EPS)
- Analysis terms
	- Price to Earnings Ratio (P/E Ratio), Fundamental Analysis, Technical Analysis, Book Value
- Type of Investment terms
	- Growth Stocks, Value Stocks, Blue Chip Stocks, Penny Stocks
- Investment strategies terms
	- Dollar Cost Averaging (DCA), Asset Allocation, Passive Investing, Active Investing
