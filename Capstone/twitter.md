Predicting Stock Market Returns with Twitter
----------------------------------------

It has been claimed that Twitter can be used to predict movement in the stock market

* [http://arxiv.org/pdf/1010.3003&](http://arxiv.org/pdf/1010.3003&)
* [http://www.bloomberg.com/news/2010-12-22/hedge-fund-will-track-twitter-to-predict-stockmarket-movements.html](http://www.bloomberg.com/news/2010-12-22/hedge-fund-will-track-twitter-to-predict-stockmarket-movements.html)
* [http://aclweb.org/anthology//P/P13/P13-2005.pdf](http://aclweb.org/anthology//P/P13/P13-2005.pdf)

In this final project you will search for social media discussion of specific stocks using the [twitteR package](http://cran.r-project.org/web/packages/twitteR/index.html) and the searchTwitter function. You will collect stock data for the S & P 500 (or some other subset) using the [quantmod](http://cran.r-project.org/web/packages/quantmod/index.html) package. You may find the text mining package [tm](http://cran.r-project.org/web/packages/tm/index.html), [tutorial](http://cran.r-project.org/web/packages/tm/vignettes/tm.pdf)

Here is an analysis that may be useful trying to analyze sentiment related to airlines [http://jeffreybreen.wordpress.com/2011/07/04/twitter-text-mining-r-slides/](http://jeffreybreen.wordpress.com/2011/07/04/twitter-text-mining-r-slides/).

### You must submit

* An R package that runs your code and produces predictions
* A vector of predictions for the returns of the first busines day after the course ends
* A write up of what you did

### You will be graded on:

* 50\% prediction RMSE
* 25\% does your R package compile 
* 25\% peer evaluation of project
  * Is the write up clear?
  * Is the code neatly documented/do what they say
  * Do the claims match the analysis
  * The rest of the rubric

### Optionally

* You can use any other data you want in your prediction
  * Your "other data" must be social media data
  * An example is the stocktwits api [http://stocktwits.com/developers/docs/api#streams-symbol-docs](http://stocktwits.com/developers/docs/api#streams-symbol-docs)
  * You must use twitter data and comment on the relative strength of this data



Digit recognizer
----------------------------------------

Have them write a digit recognizer with this:

[http://www.kaggle.com/c/digit-recognizer](http://www.kaggle.com/c/digit-recognizer)

Or we could generate simulated digits. Have them submit an R package, a prediction, and a write-up. 



Breast cancer prognosis
----------------------------------------

Have people predict breast cancer prognosis with publicly available gene expression data (data won't change much but we could rotate a few data sets)


Predicting crimes/parking tickets in B'more
----------------------------------------

[https://data.baltimorecity.gov/](https://data.baltimorecity.gov/)

Car identification in traffic cams
-----------------------------

[http://www.r-bloggers.com/machine-learning-for-identification-of-cars/](http://www.r-bloggers.com/machine-learning-for-identification-of-cars/)
[http://www.trafficland.com/city/BAL/?rsid=weatherbug](http://www.trafficland.com/city/BAL/?rsid=weatherbug)