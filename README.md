<div align="center">
	<img width="500" height="350" src="media/logo.svg" alt="Awesome">
	<br>
  <p>
    <a href="https://github.com/georgezouq/awesome-deep-reinforcement-learning-in-finance">DL/RL/SL Strategies Research & Tools in Quantitative Finance</a>
  </p>
</div>

# Awesome DL/RL/SL in Quantitative Finance

The main goal is collect those AI (RL / DL / SL / Evoluation / Genetic Algorithm) used in financial market. otherwise, we add Technology Analysis / Alpha Research / Arbitrage and other useful strategies tools & docs in quantitative finance market.

We collect all market include traditional market like `stock/futures/currencies` and crypto currency markets.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[toc]

- Papers
- Strategies
- Trading System
- Research tools
- Data Sources
- Tutorials & Docs
- Exchange API & Docs
- Other Tools

## Papers

### Basic Theory

- [THE THEORY OF SPECULATION L. BACHELIER 1900](http://www.radio.goldseek.com/bachelier-thesis-theory-of-speculation-en.pdf): The influences which determine the movements of the Stock Exchange are
- [Brownian Motion in the Stock Market Osborne,1959](http://m.e-m-h.org/Osbo59.pdf)                                                                                                                              innumerable. Events past, present or even anticipated, often showing no apparent
                                                                                                                              connection with its fluctuations, yet have repercussions on its course.

### Modern

- [A Deep Reinforcement Learning Framework for the
Financial Portfolio Management Problem](https://arxiv.org/pdf/1706.10059.pdf)
- [Reinforcement Learning for Trading 1994](http://papers.nips.cc/paper/1551-reinforcement-learning-for-trading.pdf)

## Strategies & Research

### AI

#### Traditional Markets

- [Personae](https://github.com/Ceruleanacg/Personae): 📈 Personae is a repo of implements and environment of Deep Reinforcement Learning & Supervised Learning for Quantitative Trading.
- [Quantitative-Trading](https://github.com/Ceruleanacg/Quantitative-Trading): 💸 Papers and Code Implements for Quantitative-Trading
- [gym-trading](https://github.com/hackthemarket/gym-trading): Environment for reinforcement-learning algorithmic trading models
- [zenbrain](https://github.com/carlos8f/zenbrain): A framework for machine-learning bots

#### Portfolio Management

- [qtrader](https://github.com/filangel/qtrader): Reinforcement Learning for Portfolio Management
- [PGPortfolio](https://github.com/ZhengyaoJiang/PGPortfolio): PGPortfolio: Policy Gradient Portfolio, the source code of "A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem

### High Frequency Trading (HFT)

- [SGX-Full-OrderBook-Tick-Data-Trading-Strategy](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy): Providing the solutions for high-frequency trading (HFT) strategies using data science approaches (Machine Learning) on Full Orderbook Tick Data.
- [HFT_Bitcoin](https://github.com/ghgr/HFT_Bitcoin): Analysis of High Frequency Trading on Bitcoin exchanges

#### Crypto Currencies

- [LSTM-Crypto-Price-Prediction](https://github.com/SC4RECOIN/LSTM-Crypto-Price-Prediction): Predicting price trends in cryptomarkets using an lstm-RNN for the use of a trading bot
- [tforce_btc_trader](https://github.com/lefnire/tforce_btc_trader): TensorForce Bitcoin Trading Bot
- [Tensorflow-NeuroEvolution-Trading-Bot](https://github.com/SC4RECOIN/Tensorflow-NeuroEvolution-Trading-Bot): Using tensorflow to build a population of models that trade cyrpto and breed and mutate iteratively
- [gekkoga](https://github.com/gekkowarez/gekkoga): Genetic Algorithm for solving optimization of trading strategies using Gekko
- [Gekko_ANN_Strategies](https://github.com/markchen8717/Gekko_ANN_Strategies): ANN trading strategies for the Gekko trading bot
- [gekko-neuralnet](https://github.com/zschro/gekko-neuralnet): Neural network strategy for Gekko
- [bitcoin_prediction](https://github.com/llSourcell/bitcoin_prediction): This is the code for "Bitcoin Prediction" by Siraj Raval on Youtube

### TA

- [Gekko-Bot-Resources](https://github.com/cloggy45/Gekko-Bot-Resources): Gekko bot resources.
- [gekko_tools](https://github.com/tommiehansen/gekko_tools): Gekko strategies, tools etc.
- [gekko RSI_WR](https://github.com/zzmike76/gekko): Gekko RSI_WR strategies
- [gekko HL](https://github.com/mounirlabaied/gekko-strat-hl): calculate down peak and trade on
- [EthTradingAlgorithm](https://github.com/Philipid3s/EthTradingAlgorithm): Ethereum trading algorithm using Python 3.5 and the library ZipLine
- [gekko_trading_stuff](https://github.com/thegamecat/gekko-trading-stuff): A dumping ground for my files I use with this awesome crypto currency trading platform
- [forex.analytics](https://github.com/mkmarek/forex.analytics): Node.js native library performing technical analysis over an OHLC dataset with use of genetic algorithm
- [Bitcoin_MACD_Strategy](https://github.com/VermeirJellen/Bitcoin_MACD_Strategy): Bitcoin - MACD Crossover Trading Strategy Backtest
- [crypto-signal](https://github.com/CryptoSignal/crypto-signal): Automated Crypto Trading & Technical Analysis (TA) Bot for Bittrex, Binance, GDAX, and more! (250+ coins)
- [Gekko-Strategies](https://github.com/xFFFFF/Gekko-Strategies): Strategies to Gekko trading bot with backtests results and some useful tools.
- [gekko-gannswing](https://github.com/johndoe75/gekko-gannswing): Gann's Swing trade strategy for Gekko trade bot


### Arbitrage

- [ArbitrageBot](https://github.com/BatuhanUsluel/ArbitrageBot): Arbitrage bot that currently works on bittrex & poloniex
- [r2](https://github.com/bitrinjani/r2): R2 Bitcoin Arbitrager is an automatic arbitrage trading system powered by Node.js + TypeScript.
- [cryptocurrency-arbitrage](https://github.com/manu354/cryptocurrency-arbitrage): A cryptocurrency arbitrage opportunity calculator. Over 800 currencies and 50 markets. https://cryptoworks.co
- [bitcoin-arbitrage](https://github.com/maxme/bitcoin-arbitrage): Bitcoin arbitrage - opportunity detector
- [blackbird](https://github.com/butor/blackbird): Blackbird Bitcoin Arbitrage: a long/short market-neutral strategy


## Data Sources

#### Traditional Markets

- [Tushare](): 

#### Crypto Currencies

- [CryptoInscriber](https://github.com/Optixal/CryptoInscriber): 📈 A live cryptocurrency historical trade data blotter. Download live historical trade data from any cryptoexchange, be it for machine learning, backtesting/visualizing trading strategies or for Quantopian/Zipline.
- [Gekko-Datasets](https://github.com/xFFFFF/Gekko-Datasets): Gekko Trading Bot dataset dumps. Ready to use and download history files in SQLite format.


## Research Tools

- [JAQS](https://github.com/quantOS-org/JAQS): An open source quant strategies research  platform.
- [pyfolio](https://github.com/quantopian/pyfolio): Portfolio and risk analytics in Python https://quantopian.github.io/pyfolio
- [alphalens](https://github.com/quantopian/alphalens): Performance analysis of predictive (alpha) stock factors http://quantopian.github.io/alphalens
- [empyrical](https://github.com/quantopian/empyrical): Common financial risk and performance metrics. Used by zipline and pyfolio. http://quantopian.github.io/empyrical

## Trading System (Back Test & Live trading)

### Traditional Market

[System]

- [zipline](https://github.com/quantopian/zipline): Zipline, a Pythonic Algorithmic Trading Library http://www.zipline.io/
- [rqalpha](https://github.com/ricequant/rqalpha): A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities http://rqalpha.io
- [backtrader](https://github.com/backtrader/backtrader): Python Backtesting library for trading strategies https://www.backtrader.com
- [kungfu](https://github.com/taurusai/kungfu): Kungfu Master Trading System

[Combine & Rebuild]

- [pylivetrader](https://github.com/alpacahq/pylivetrader): Python live trade execution library with zipline interface.
- [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting): This project tests bt(http://pmorissette.github.io/bt) and Quantopian Zipline(https://github.com/quantopian/zipline) as backtesting frameworks for coin trading strategy.

### Crypto Currencies

- [gekko](https://github.com/askmike/gekko): A bitcoin trading bot written in node - https://gekko.wizb.it/
- [zenbot](https://github.com/DeviaVir/zenbot): Zenbot is a command-line cryptocurrency trading bot using Node.js and MongoDB.
- [bot18](https://github.com/carlos8f/bot18): Bot18 is a high-frequency cryptocurrency trading bot developed by Zenbot creator @carlos8f https://bot18.net/
- [magic8bot](https://github.com/magic8bot/magic8bot): Magic8bot is a cryptocurrency trading bot using Node.js and MongoDB.
- [catalyst](https://github.com/enigmampc/catalyst): An Algorithmic Trading Library for Crypto-Assets in Python http://enigma.co
- [QuantResearchDev](https://github.com/mounirlabaied/QuantResearchDev): Quant Research dev & Traders open source project **[BUILDING]**
- [MACD](https://github.com/sudoscripter/MACD): Zenbot Macd Auto-Trader
- [abu](https://github.com/bbfamily/abu): A quant trading system base on python.http://www.abuquant.com/

#### Plugins

- [easytrader](https://github.com/shidenggui/easytrader): 提供银河/国金/华泰客户端/同花顺客户端/雪球的基金、股票自动程序化交易以及自动打新，支持跟踪 joinquant /ricequant 模拟交易 和 实盘雪球组合, 量化交易组件
- [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting): This project tests bt(http://pmorissette.github.io/bt) and Quantopian Zipline(https://github.com/quantopian/zipline) as backtesting frameworks for coin trading strategy.
- [Gekko-BacktestTool](https://github.com/xFFFFF/Gekko-BacktestTool): Batch backtest, import and strategy params optimalization for Gekko Trading Bot. With one command you will run any number of backtests.

### TA (Technology Analysis) Lib

- [pandas_talib](https://github.com/femtotrader/pandas_talib): A Python Pandas implementation of technical analysis indicators
- [tulipnode](https://github.com/TulipCharts/tulipnode): Tulip Node is the official node.js wrapper for Tulip Indicators. It provides over 100 technical analysis overlay and indicator functions. https://tulipindicators.org
- [techan.js](https://github.com/andredumas/techan.js): A visual, technical analysis and charting (Candlestick, OHLC, indicators) library built on D3. http://techanjs.org/


### Exchange API

- [HuobiFeeder](https://github.com/mmmaaaggg/HuobiFeeder): Connect HUOBIPRO exchange, get market/historical data for ABAT trading platform backtest/analysis and live trading

## Tutorials

### ML

- [Reinforcement-learning-with-tensorflow](https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow): Simple Reinforcement learning tutorials
- [Algorithm_Interview_Notes-Chinese](https://github.com/imhuay/Algorithm_Interview_Notes-Chinese): Algorithm Interview Notes Chinese
- [Learning-Notes](https://github.com/Ceruleanacg/Learning-Notes): 💡 Repo of learning notes in DRL and DL, theory, codes, models and notes maybe.
- [Deep-Learning-World](https://github.com/astorfi/Deep-Learning-World): 📡 Organized Resources for Deep Learning Researchers and Developers
- [100-Days-Of-ML-Code](https://github.com/Avik-Jain/100-Days-Of-ML-Code): 100 Days of ML Coding

### Quant

## AI Framework

- [convnetjs](https://github.com/karpathy/convnetjs): Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
- [TensorForce](https://github.com/reinforceio/tensorforce): TensorForce: A TensorFlow library for applied reinforcement learning
- [gym](https://github.com/openai/gym): A toolkit for developing and comparing reinforcement learning algorithms. https://gym.openai.com/
- [Pavlov.js](https://github.com/NathanEpstein/Pavlov.js): Reinforcement learning using Markov Decision Processes. For JS, written in C++.


### Visualizing

- [playground](https://github.com/tensorflow/playground): Play with neural networks! http://playground.tensorflow.org
- [netron](https://github.com/lutzroeder/netron): Visualizer for deep learning and machine learning models https://www.lutzroeder.com/ai


## Articles

#### Chinese

- [Maury Osborne和三文鱼的故事](https://zhuanlan.zhihu.com/p/20586843)
- [布朗运动、伊藤引理——细说Black-Scholes公式的前世今生（上篇）](https://zhuanlan.zhihu.com/p/32664487) 
- [布朗运动、伊藤引理——细说Black-Scholes公式的前世今生（下篇）](https://zhuanlan.zhihu.com/p/32746192)
- [趋势策略小试牛刀，海龟交易体系的构建](https://www.ricequant.com/community/topic/62/%E8%B6%8B%E5%8A%BF%E7%AD%96%E7%95%A5%E5%B0%8F%E8%AF%95%E7%89%9B%E5%88%80-%E6%B5%B7%E9%BE%9F%E4%BA%A4%E6%98%93%E4%BD%93%E7%B3%BB%E7%9A%84%E6%9E%84%E5%BB%BA)

## Others

- [zipline-tensorboard](https://github.com/jimgoo/zipline-tensorboard): TensorBoard as a Zipline dashboard http://jimgoo.com/tensorboard-and-zip…
- [gekko-quasar-ui](https://github.com/H256/gekko-quasar-ui): An UI port for gekko trading bot using Quasar framework.

#### Other Resource

- [awesome-quant](https://github.com/wilsonfreitas/awesome-quant): A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance)          
- [awesome-quant-china](https://github.com/thuquant/awesome-quant): Quant resource in china

