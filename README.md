# FALCON_C

Designed to work best with Decision Support System developed inside Lazy Trading Project

https://vladdsm.github.io/myblog_attempt/topics/lazy%20trading/

# Introduction

Rule-based trading robot. Main features are listed below:

* Capability to contain different rules for different Market Types
* Market Type recognized Using Deep Learning Supervised Classification Model on time series data (code is in separate repository):
- R code using h2o deep learning framework
- pre-train Deep Learning on previously selected labelled markets. 
- MACD metric is used as a sole asset metric considered for the model
- New data are fit continuously to the model and it tries to recognize the market.
- Market status is supplied further to the MQL 4 trading strategy

# Reference

Functionality of this EA is explained in the Udemy course [Lazy Trading Part 6: Detect Market status with AI](https://www.udemy.com/detect-market-status-with-ai/?couponCode=LAZYTRADE6-10)

# Disclaimer

Use on your own risk: past performance is no guarantee of the future results!