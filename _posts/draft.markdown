---
layout: post
title:  
date:   2019-08-04=5 00:30:40 -0400
categories:
---

A lot of AI/ML has become commoditized, packaged in products that spits out analysis. Where the data scientist's expertise is neccessary is in tuning model parameters, interpreting results, differentiating between algorithims.


This is a quick way to look at correlations between variables:
`import pandas as pd
df = http://pd.read_csv(client_data)
pwcorr = df.corr(method='pearson').unstack().sort_values()
print(pwcorr)`
