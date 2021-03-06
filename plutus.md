---
layout: page
title: Plutus
---

[BOOK](https://towardsdatascience.com/aifortrading-2edd6fac689d). Using the latest advancements in deep learning to predict stock prices.

[Detecting SR levels](https://towardsdatascience.com/detection-of-price-support-and-resistance-levels-in-python-baedc44c34c9)


Bayesian optimisation to tune hyperparameters. Useful for optimising 'black-box' functions where we do not know it's explicit form.

Applying Digital Filters and Spectral Analysis to Signals from charts.

deltaquants.com

[Kaggle free courses](https://www.kaggle.com/learn/overview)

Podcasts:

* https://www.pythonpodcast.com/
* https://changelog.com/practicalai
* https://talkpython.fm/episodes/all
* https://www.talkrl.com/
* https://ocdevel.com/mlg

---

[__Use VPVR for S/R levels__](https://tcoil.info/volume-profile-for-stocks-in-python-vpvr-indicator-volume-profile-visible-range/)

---

## Key Performance Metrics

* Graph of Cumulative profits over time.
* Average rate of return
* Variability of returns over time
* worst peak-to-valley drawdowns
* R-squared
* time decay*

Graphs:

* Cumulative Returns vs BTC
* Cumulative Returns vs BTC (log scaled)
* Cumulative Returns vs BTC (volatility matched)
* EOY returns vs BTC
* Distribution of monthly returns
* Rolling Beta to BTC
* Rolling volatility (6-months)

Table as follows:

Metric - asset - BTC

* Risk-free rate
* time in market
* cumulative return 
* CAGR%
* Sharpe
* Sortino
* Max Drawdown
* Longest drawdown (days)
* Volatility (annualised)
* R^2
* Calmar
* Skew
* Kurtosis
* Expected daily %
* Expected Monthly %
* Expected yearly %
* Kelly Criterion
* Risk of Ruin
* Daily value-at-risk
* Expected shortfall (cVaR)
* Payoff ratio
* Profit factor
* Common sense ratio
* CPC index
* Tail ratio
* Outlier win ratio
* Outlier loss ratio
* MTD

Also: correlation of every cryptocurrency with every other cryptocurrency

## Indicators

I = Implemented.

P = Plottable

Entry, Exit... = Tested as entry indicator in NNFX model

Name | type | I | P | Entry | Exit | Baseline | Vol | TrailSL | Comments
:---:|:----:|:-:|:-:|:-----:|:----:|:--------:|:---:|:------: | :------:
EMA  | overlap | X | X |       |      |          |     |  
DEMA  |  | X |       |      |          |     |  
TEMA  |  | X |       |      |          |     |  
TRIMA  |  | X |       |      |          |     |  
SMA |  | X |       |      |          |     |  
WMA |  | X |       |      |          |     |  
T3 |  | X |       |      |          |     |  
KAMA |  | X |       |      |          |     |  
LeastSquaresMA  |  |  |       |      |          |     |  
WellesMA |  |  |       |      |          |     |  
VariableMA |  |  |       |      |          |     |  
VolumeWeightedMA |  |  |       |      |          |     |  
ZeroLagEMA |  |  |       |      |          |     |  
MAMA |  |  |       |      |          |     |  
MACD |  | X |       |      |          |     |  
MACDExt |  |  |       |      |          |     |  
Stochastic |  | No |       |      |          |     |  
StochasticRSI |  | No |       |      |          |     |  
MAVP |  | X |       |      |          |     |  | |matype=0. TODO - Allow to change setting. 
MidPoint |  | X |       |      |          |     |  
MidPrice |  | X |       |      |          |     |  
HT_Trendline |  | X |       |      |          |     |  
ParabolicSAR |  | X |       |      |          |     |  | |I like how it accelerates as trend develops
ParabolicSARExt |  |  |       |      |          |     |  
Pivot Points|  |  |       |      |          |     |  
Kijun Sen ||X|||||
Tenkan Sen ||X|||||
ADX | momentum | X |       |      |          |     |  
ADXRating |  | X |       |      |          |     |  
APO |  | X |       |      |          |     |  
Aroon |  | X |       |      |          |     |  
AroonOsc |  | X |       |      |          |     |  
BOP |  | X |       |      |          |     |  
CCI |  | X |       |      |          |     |  
CMO |  | X |       |      |          |     |  
DX |  | X |       |      |          |     |  
MFI |  | X |       |      |          |     |  
Momentum |  | X |       |      |          |     |  
Mass Index|  | X |       |      |          |     |  
PPO |  | X |       |      |          |     |  | |matype=0. TODO - Allow to change setting.
RSI |  | X |       |      |          |     |  
RVI |  |  |       |      |          |     |  
ROC |  | X |       |      |          |     |  
TSI |  |  |       |      |          |     |  
WilliamsR |  | X |       |      |          |     |  
UltimateOsc |  | X |       |      |          |     |  
VHF |  | X |       |      |          |     |  
Volume | volume | X | X |      |          |     |  
ChaikinAD | | X |       |      |          |     |  
ChaikinADOsc|  | X |       |      |          |     |  
Ease of Movement|  |  |       |      |          |     |  
OBV|  | X |       |      |          |     |  
PVO|  |  |       |      |          |     |  
DPO|  | X | X |      |          |     |  
CMF|  |  |       |      |          |     |  
VPT|  |  |       |      |          |     |  
VWAP|  |  |       |      |          |     |  
KST Oscillator|  |  |       |      |          |     |  
Force Index (FI)|  |  |       |      |          |     |  
Positive Volume Index |  |  |       |      |          |     |  
Negative Volume Index|  |  |       |      |          |     |  
ADI|  |  |       |      |          |     |  
HT_DominantCyclePeriod|cycles| X |     |    |     |    |  
HT_DominantCyclePhase|  | X |     |      |          |     |
HT_Phasor Components Real|  | X |     |      |          |     | 
HT_Phasor Components Imaginary|  | X |     |      |          |     | 
HT_TrendMode|  | X |     |      |          |     | 
AveragePrice|price transforms| X |   |    |   |     |  
MedianPrice|  | X |     |    |      |     |  
TypicalPrice|  | X |     |     |      |     |  
WeightedClosePrice|  | X |       |      |          |     |  
ATR| volatility | X |  |      |          |     |  
NATR|  | X |       |      |          |     |  
TRANGE|  | X |       |      |          |     |  
Chaikin's Volatility|  |  |       |      |          |     |  
---|  |  |       |      |          |     |  
Trix| momentum | X | X |      |          |     |  
Vortex Indicator|  |  |       |      |          |     |  
Awesome Oscillator|  | No |       |      |          |     |  
Vector Ceiling|  |  |       |      |          |     |  
Vector Floor|  |  |       |      |          |     |  
Fisher Transform|  |  |       |      |          |     |  
Forecast Oscillator|  |  |       |      |          |     |  
Klinger Volume Oscillator|  |  |       |      |          |     |  
Williams Accumulation/Distribution|  |  |       |      |          |     |  
Wilders Smoothing|  |  |       |      |          |     |  
Mass Index| Trend | X | X |      |          |     |  
Renko|  | X |       |      |          |     |  
VPVR|  |  |       |      |          |     |  
Fractal Highs|  |  |       |      |          |     |  
Fractal Lows|  |  |       |      |          |     |  
Qualitative/Quantitative Estimator (QQE)|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |    
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
|  |  |       |      |          |     |  
