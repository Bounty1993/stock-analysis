# Stock market analysis

The purpose of the project is to analysis stock market indicators and assess how accurate
 they predict future. [Monte Carlo](https://pl.wikipedia.org/wiki/Metoda_Monte_Carlo) simulation was 
 used to show possible future changes in prices. After that most popular stock market indicators was used and
 compared with "Buy & Hold" strategy. Data comes from [stooq.pl](https://stooq.pl/)
 
 *Indicators used*:
 * [RSI](https://en.wikipedia.org/wiki/Relative_strength_index)
 * [Bollinger Bands](https://en.wikipedia.org/wiki/Bollinger_Bands)
 * [MACD](https://en.wikipedia.org/wiki/MACD)
 * [Moving Average](https://en.wikipedia.org/wiki/Moving_average)
 
 ### Installation
 
 First of all, create virtual environment or use Pipenv and then:
 
 ```
 $ git clone https://github.com/Bounty1993/stock-analysis.git
 $ cd stock-analysis
 $ pip install -r requirements.txt
 ```
 Now you can use wig_analysis.ipynb with Jupyter Notebook. The project uses classes so it should be easy to reuse them
 
 
 *Project will be futher developed and new indicators will be used*