---
layout: post
title: Links
# permalink: /links/
---

## Portfolio Projects
- [ ] Text-based
  - Instagram NLP too??
- [ ] Image project
  - [ ] Create own Instagram dataset for deep learning. Example: https://github.com/rememberlenny/streetart-notstreetart, tutorial https://blog.floydhub.com/instagram-street-art/
- [ ] Time series analysis. Use: https://www.ethanrosenthal.com/2018/03/22/time-series-for-scikit-learn-people-part2/
- [ ] A/B testing/hypothesis testing
- [ ] Visualization
  - [ ] MoMA
- [ ] Geo-mapping
  - [ ] Build week: deforestation
- [ ] Really intense data cleaning (multiple datasets, missing data that requires imputation)
  - [ ] potentially, MoMA
- [ ] Regression analysis (comparing multiple methods)
- [ ] Something that uses SQL
- [ ] Full stack deployment
  - [ ] Build week: deforestation

Each project should have:
- [ ] reproducible & follow best practices (PublicArt has a great readme)
- [ ] put functions in separate file and import them, split data cleaning and data analysis/modelling
- [ ] Use a style guide (PEP8)
- [ ] Executive summary in the Readme or notebook: get to the point! What did you, why did you do it and why is it important? If you use a particularly unusual technique, can you explain it and show that it preforms better than some baseline (e.g. regression).

Great examples (and custom datasets):
- http://cs229.stanford.edu/proj2018/
- http://cs229.stanford.edu/proj2019spr/report/25.pdf
- http://cs229.stanford.edu/proj2019spr/report/52.pdf
- http://cs229.stanford.edu/proj2019spr/report/75.pdf

## How to write up a project?
- Predicting Time to Cook, Arrive, and Deliver at Uber Eats [[link]](https://www.infoq.com/articles/uber-eats-time-predictions/)
- Using R and SQL to Advocate for Harlem Housing Repairs [[link]](https://towardsdatascience.com/using-r-and-sql-to-advocate-for-harlem-housing-repairs-8b7557644a63)
- Bayesian Product Ranking at Wayfair [[link]](https://tech.wayfair.com/data-science/2020/01/bayesian-product-ranking-at-wayfair/?utm_campaign=Data_Elixir&utm_source=Data_Elixir_269)
- List of great case studies [[link]](https://twitter.com/chipro/status/1188650188392390656)
  - Using Machine Learning to Predict Value of Homes on AirBnB [[link]](https://medium.com/airbnb-engineering/using-machine-learning-to-predict-value-of-homes-on-airbnb-9272d3d4739d)
  - Using Machine Learning to Improve Streaming Quality at Netflix [[link]](https://netflixtechblog.com/using-machine-learning-to-improve-streaming-quality-at-netflix-9651263ef09f)
  - From shallow to deep learning in fraud [[link]](https://eng.lyft.com/from-shallow-to-deep-learning-in-fraud-9dafcbcef743)
  - Space, Time and Groceries [[link]](https://tech.instacart.com/space-time-and-groceries-a315925acf3a)
  - How we grew from 0 to 4 million women on our fashion app, with a vertical machine learning approach [[link]](https://medium.com/hackernoon/how-we-grew-from-0-to-4-million-women-on-our-fashion-app-with-a-vertical-machine-learning-approach-f8b7fc0a89d7)
  - Machine Learning-Powered Search Ranking of Airbnb Experiences [[link]](https://medium.com/airbnb-engineering/machine-learning-powered-search-ranking-of-airbnb-experiences-110b4b1a0789)
  - Creating a Modern OCR Pipeline Using Computer Vision and Deep Learning [[link]](https://blogs.dropbox.com/tech/2017/04/creating-a-modern-ocr-pipeline-using-computer-vision-and-deep-learning/)

## Building a portfolio/website
- Pin repos with strong work, have descriptive titles and a brief readme (include an image)
- examples:
  - [[link1]](https://twitter.com/alyssaxuu/status/1148253489144979456)
  - went viral [[link2]](https://www.jeffykao.com/)
  - [[link3]](https://krsmith.github.io/aboutme/)

## Python
- Best of the best practices guide for Python [[link]](https://gist.github.com/sloria/7001839)


## Bayesian Hierarchical/Multi-level Modeling
- How to do Hierarchical Linear Regression in PyMC3 (uses Radon dataset) [[link]](https://twiecki.io/blog/2014/03/17/bayesian-glms-3/)
- Paper: Analysis of Local Decisions Using Hierarchical Modeling, Applied to Home Radon Measurement and Remediation [[link]](http://www.stat.columbia.edu/~gelman/research/published/lin.pdf)
- Paper: Understanding the Average Impact of Microcredit Expansions: A Bayesian Hierarchical Analysis of Seven Randomized Experiments[[link]](https://pdfs.semanticscholar.org/add4/5613b77be86a01d51555e4940462ef633942.pdf)

## Open Data
- Jordà-Schularick-Taylor Macrohistory Database [[link]](http://www.macrohistory.net/data/)
- Great Github list of public data sets [[link]](https://www.datasciencecentral.com/profiles/blogs/great-github-list-of-public-data-sets?overrideMobileRedirect=1)
- A collection of museum, gallery, library, archive, archaeology and assorted sources for machine-readable data [[link]](http://museum-api.pbworks.com/w/page/21933420/Museum%C2%A0APIs)
  - [[The Museum of Modern Art (MoMA) Collection]](https://github.com/MuseumofModernArt/collection): This research dataset contains 138,567 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date made, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not Curator Approved." The Artists dataset contains 16,030 records, representing all the artists who have work in MoMA's collection and have been cataloged in our database. It includes basic metadata for each artist, including name, nationality, gender, birth year, death year, Wiki QID, and Getty ULAN ID. [[in the wild]](https://medium.com/@foe/here-s-a-roundup-of-how-people-have-used-our-data-so-far-80862e4ce220#.f6272outn). Update status: automatic monthly update
  - [[Feeding America: The Historic American Cookbook Dataset]](https://lib.msu.edu/feedingamericadata/)
  - [[The Museum of Modern Art (MoMA) Exhibition and Staff Histories]](https://github.com/MuseumofModernArt/exhibitions): This research dataset lists 1,788 exhibitions, representing all of the known exhibitions held at the museum from 1929 through 1989. All known curators and organizers, artists and other participants are listed for each exhibition. A total of 11,550 constituents are represented in this dataset, approximately 5,900 of them not currently represented in MoMA’s permanent collection of artworks. Update status: 2016
  - [[British Library]](https://data.bl.uk/): lots within here
  - [[Cooper Hewitt, Smithsonian Design Museum]](https://github.com/cooperhewitt/collection): This departments, exhibitions, objects, people, periods, roles and types folders contain Cooper Hewitt collection data exported as individual JSON files. Update status: 2017
  - [[The Tate Collection]](https://github.com/tategallery/collection): Here we present the metadata for around 70,000 artworks that Tate owns or jointly owns with the National Galleries of Scotland as part of ARTIST ROOMS. Metadata for around 3,500 associated artists is also included. Status update: 2014, not being updated
- Reddit [[link]](https://www.reddit.com/r/datasets/)
- KDnuggets [[link]](https://www.kdnuggets.com/datasets/index.html?source=post_page---------------------------)
- Socioeconomic High-resolution Rural-Urban Geographic panel for India (SHRUG) -- release Aug 25 [[link]](http://www.dartmouth.edu/~novosad/data.html)
- China’s Maritime Silk Road: data not public yet [[link]](https://haralambides-mel.blogspot.com/2019/06/riding-along-chinas-maritime-silk-road.html)
- Ontario Data Catalogue [[link]](https://stage.data.ontario.ca/)
- JPAL [[link]](https://dataverse.harvard.edu/dataverse/DFEEP)
- Urban Institute Catalogue [[link]](https://datacatalog.urban.org/search/type/dataset)
- QuantGov [[link]](https://quantgov.org/state-regdata/)

## Reproducible DS projects
- cookiecutter Python package for folder setup, virtualenv, and privacy [[link]](https://drivendata.github.io/cookiecutter-data-science/)
- Coding conventions, documenting, cookiecutter, git, data version control, virtual envs, notebooks [[link]](https://towardsdatascience.com/down-with-technical-debt-clean-python-for-data-scientists-aa7592eff7fc)
- FB custom built a reproducible pipeline [[link]](https://engineering.fb.com/ml-applications/introducing-fblearner-flow-facebook-s-ai-backbone/)
- How Uber scaled ML as a service [[link]](http://proceedings.mlr.press/v67/li17a/li17a.pdf)

## Spark
- Guide to columnar file formats (parquet, ORC) [[link]](https://blog.matthewrathbone.com/2019/11/21/guide-to-columnar-file-formats.html?utm_campaign=The%20Data%20Science%20Roundup&utm_medium=email&utm_source=Revue%20newsletter)

## Imbalanced Classes
- Learning from Imbalanced Classes [[link]](https://www.svds.com/tbt-learning-imbalanced-classes/)

## Causation
- A Second Chance to Get Causal Inference Right: A Classification of Data Science Tasks [[link]](https://amstat.tandfonline.com/doi/full/10.1080/09332480.2019.1579578#.XWtAJZNKjBJ)
- First workshop on bridging causal inference, RL and transfer learning [[link]](https://crt2019.github.io/)

## AutoML
- Towards Automated Machine Learning: Evaluation and Comparison of AutoML Approaches and Tools [[link]](https://arxiv.org/abs/1908.05557)

## Experimental Design
- how to choose sample sizes in A/B testing or ML iterations [[link]](https://chris-said.io/2020/01/10/optimizing-sample-sizes-in-ab-testing-part-I/?utm_campaign=The%20Data%20Science%20Roundup&utm_medium=email&utm_source=Revue%20newsletter)

## SQL
- Udacity SQL course [[link]](https://www.udacity.com/course/sql-for-data-analysis--ud198)
- One SQL to Rule Them All [[paper]](https://arxiv.org/abs/1905.12133)]
- SQL Style Guide [[link]](https://github.com/mattm/sql-style-guide)
- Example SQL screener question [[link]](https://mattmazur.com/2018/11/12/analyzing-89-responses-to-a-sql-screener-question-for-a-senior-data-analyst-position/)
- Learning SQL 201: Optimizing Queries, Regardless of Platform [[link]](https://towardsdatascience.com/learning-sql-201-optimizing-queries-regardless-of-platform-918a3af9c8b1)
- A Cool SQL Problem: Avoiding For-Loops [[link]](https://ryxcommar.com/2019/08/05/a-cool-sql-problem-avoiding-for-loops/)
- SQL interviews at the NYT [[link]](https://open.nytimes.com/a-window-into-our-sql-interviews-dcc9a8f756d8)
- SQL live coding [[link]](https://twitter.com/BecomingDataSci/status/1178184449890095111)
- Loooong SQL queries [[link]](https://twitter.com/b0rk/status/1175068822107279362)
- Bootstrapping is the most intuitive way to teach inference in introductory stats courses. [[link]](https://twitter.com/grant_mcdermott/status/1175576565863702528)
- How Postgres Makes Transactions Atomic [[link]](https://brandur.org/postgres-atomicity)
- SQL query order [[link]](https://twitter.com/b0rk/status/1179449535938076673)

## Modeling
>A statistical model is a mathematical model which is modified or trained by the input of data points. Statistical models are often but not always probabilistic. Where the distinction is important we will be careful not to just say "statistical" but to use the following component terms:
A mathematical model specifies a relation among variables, either in functional form that maps inputs to outputs (e.g. y = m x + b) or in relation form (e.g. the following (x, y) pairs are part of the relation).
A probabilistic model specifies a probability distribution over possible values of random variables, e.g., P(x, y), rather than a strict deterministic relationship, e.g., y = f(x).
A trained model uses some training/learning algorithm to take as input a collection of possible models and a collection of data points (e.g. (x, y) pairs) and select the best model. Often this is in the form of choosing the values of parameters (such as m and b above) through a process of statistical inference.

- Different types of models [[link]](http://norvig.com/chomsky.html)
- Cool datasets [[link]](https://cooldatasets.com/)
- Great guide to using predicted probabilities for a threshold model [[link]](https://blog.insightdatascience.com/visualizing-machine-learning-thresholds-to-make-better-business-decisions-4ab07f823415)

## Others
- how to make a personal Python toolbox [[link]](https://brohrer.github.io/personal_toolbox.html)
- analyzing 100GB of data with Vaex, example using NYC taxi dataset [[link]](https://towardsdatascience.com/how-to-analyse-100s-of-gbs-of-data-on-your-laptop-with-python-f83363dda94)
- very detailed POV into data science consulting [[link]](https://www.ethanrosenthal.com/2020/01/08/freelance-ds-consulting/?utm_campaign=The%20Data%20Science%20Roundup&utm_medium=email&utm_source=Revue%20newsletter)
- The diminishing returns of incremental data, or why "data is rarely a strong enough moat" [[link]](https://a16z.com/2019/05/09/data-network-effects-moats/)
- My secret sauce to be in top 2% of a kaggle competition [[link]](https://towardsdatascience.com/my-secret-sauce-to-be-in-top-2-of-a-kaggle-competition-57cff0677d3c)
- Interviews with Machine Learning Heroes [[link]](https://hackernoon.com/interviews-with-machine-learning-heroes-504762ba5dd6)
- Getting Started With Data Science (concrete advice)
[[link]](https://medium.com/@Imaadmkhan1/getting-started-with-data-science-c35893b3e796)
- Chris Albon's technical notes
[[link]](https://chrisalbon.com/)
- Interesting Juptyer notebooks
[[link]](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
- Dagster: A open-source Python library for building data applications [[link]](https://medium.com/@schrockn/introducing-dagster-dbd28442b2b7)
- Getting a normcore tech job [[link]](https://old.reddit.com/r/cscareerquestions/comments/cbkwp4/my_cs_story_contradicts_everything_ive_read_on/)
- Ten Simple Rules for Reproducible Research in Jupyter Notebooks / [[link]](https://arxiv.org/abs/1810.08055)
- Ten Simple Rules for Reproducible Computational Research [[link]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)
- Statistical tests, P values, confidence intervals, and power: a guide to misinterpretations [[link]](https://link.springer.com/article/10.1007/s10654-016-0149-3)
- What Are We Weighting For? [[link]](https://www.nber.org/papers/w18859)
- Guide to Python’s Data Visualization Landscape (including ggplot and Altair) [[link]](https://dsaber.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/)
- A Programmer’s Intuition for Matrix Multiplication [[link]](https://betterexplained.com/articles/matrix-multiplication/)
- An overview of gradient descent optimization algorithms [[link]](http://ruder.io/optimizing-gradient-descent/)
- How to set up a perfect Python project
[[link]](https://sourcery.ai/blog/python-best-practices/)
- Dates, Times, Calendars— The Universal Source of Data Science Trauma [[link]](https://towardsdatascience.com/dates-times-calendars-the-universal-source-of-data-science-trauma-92a887fdedd1)
- Notify when done [[link]](https://github.com/ShopRunner/jupyter-notify)

## Amazing examples of big data analysis
- Global labor flow network (Linkedin data) [[link]](https://www.nature.com/articles/s41467-019-11380-w)

## Flask
- Video walkthrough of how to an ML model with Flask and Heroku (from SharpestMinds) [[link]](https://www.youtube.com/watch?v=OdYpNM05e9w)
Create An API To Deploy Machine Learning Models Using Flask and Heroku [[link]](https://towardsdatascience.com/create-an-api-to-deploy-machine-learning-models-using-flask-and-heroku-67a011800c50)
- HTTP [[link]](https://gumroad.com/l/http-zine)

## Unit Test
- How to unit test machine learning code. [[link]](https://medium.com/@keeper6928/how-to-unit-test-machine-learning-code-57cf6fd81765)

## Cheatsheets & packages
- Matplotlib [[link1]](https://github.com/rougier/matplotlib-cheatsheet)
  - Figures hold axes, axes hold everything else [[link]](https://t.co/9sB9n7y6RB?amp=1)
- Best guide to using Matplotlib [[link]](https://pbpython.com/effective-matplotlib.html)
- econtools: econometric functions and convenient shortcuts for data work with pandas and numpy [[link]](https://github.com/dmsul/econtools)
- default export to: pandas to_csv()'s quoting=csv.QUOTE_NONNUMERIC [[link]](https://twitter.com/pybokeh/status/1216312458694053888?s=20)

## R
- ACLU: we use the Tidyverse’s dplyr to generate complex SQL code in our data warehouse [[link]](https://medium.com/aclu-tech-analytics/dbplyr-a-path-to-more-inclusive-data-transformations-at-the-aclu-5e6af21f4042)
- Really great R tutorial using example with screenshots [[link]](https://hockey-graphs.com/2019/12/11/an-introduction-to-r-with-hockey-data/)

## Neural Networks
- What does it mean to understand a neural network?
[[paper]](https://arxiv.org/abs/1907.06374)
- Neural Network Visualization
[[course]](https://end-to-end-machine-learning.teachable.com/p/neural-network-visualization/)
- A Recipe for Training Neural Networks
[[link]](https://karpathy.github.io/2019/04/25/recipe/)
- Are We Really Making Much Progress? A Worrying Analysis of Recent Neural Recommendation Approaches
[[link]](https://arxiv.org/abs/1907.06902)
- Parameter optimization in neural networks [[link]](https://www.deeplearning.ai/ai-notes/optimization/)
- Checklist for debugging neural networks [[link]](https://towardsdatascience.com/checklist-for-debugging-neural-networks-d8b2a9434f21)

> Roughly, a topic is a collection of words representative of a particular textual grouping. The words like gun and murder are perhaps more often found in detective fiction rather than erotica, for example. So remember this: topics are bags of words. Crucially, unsupervised1 topic modelling involves logic for the discovery of arbitrary word groupings. We are asking a machine to organize a pile of texts into stacks by “the difference that makes the largest difference.” From the many ways of grouping or classifying a collection of texts, we want those groups that are most starkly different from each other. Often these machine-generated “topics” track human-derived, social categories such as authors or genres. And sometimes these “topics” don’t make any (human) sense. They can indicate a difference for which no social, cultural category can exist—which is kind of fun to explore in any case. [[link]](https://denten.plaintext.in/think.stack/time-and-topics)

- Parameter optimization in neural networks [[link]](https://www.deeplearning.ai/ai-notes/optimization/)
- A Neural Network in 11 lines of Python (Part 1) [[link]](https://iamtrask.github.io/2015/07/12/basic-python-network/)
- TensorFlow 2.0 + Keras Crash Course [[link]](https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO#scrollTo=MfO_uy61upRm)
- The Unreasonable Effectiveness of Recurrent Neural Networks [[link]](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- How to Grid Search Hyperparameters for Deep Learning Models in Python With Keras [[link]](https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/)

## R
- R & Python workflow [[link]](https://towardsdatascience.com/guide-to-r-and-python-in-a-single-jupyter-notebook-ff12532eb3ba)

## Machine learning
- Online book on limitations of interpretable ML methods [[link]](https://compstat-lmu.github.io/iml_methods_limitations/)
- Optimal ML classification decision boundaries with very helpful animation [[link]](https://mathformachines.com/posts/decision/) [[gifs]](https://github.com/ryanholbrook/decision-boundaries-animations)
- Building machine learning products: workflow [[link]](https://www.jeremyjordan.me/ml-requirements/)
- [[course]](https://sites.google.com/view/marcdeisenroth/teaching/mooc-mathematics-for-machine-learning-pca)
- How to ship ML in practice [[tweet]](https://twitter.com/mlpowered/status/1151235526407553024)
- Interactive visualization of machine learning evaluation metrics [[link]](https://twitter.com/d_haitz/status/1161005970044203010)
- Animations with receiver operating characteristic and precision-recal curves [[link]](https://github.com/dariyasydykova/open_projects/tree/master/ROC_animation)
- Machine Learning Model Evaluation: Visual & Interactive [[link]](https://machine-learning-visualization.herokuapp.com/)
- Python Libraries for Interpretable Machine Learning [[link]](https://towardsdatascience.com/python-libraries-for-interpretable-machine-learning-c476a08ed2c7)
- A visual introduction to machine learning
[[link]](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- Machine Learning Model Evaluation: Visual & Interactive [[link]](https://machine-learning-visualization.herokuapp.com/)
- ML Reproducibility Checklist [[link]](https://www.cs.mcgill.ca/~jpineau/ReproducibilityChecklist.pdf)
- What machine learning theory do I need to know in order to be a successful machine learning practitioner? [[link]](https://www.quora.com/What-machine-learning-theory-do-I-need-to-know-in-order-to-be-a-successful-machine-learning-practitioner/answer/Yisong-Yue)
- TensorFlow 2.0 + Keras Crash Course [[link]](https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO)
- Reconciling modern machine learning practice and the bias-variance trade-off [[link]](https://arxiv.org/abs/1812.11118)

## Bayesian inference
Python code [[link]](https://github.com/WillKoehrsen/ai-projects/blob/master/bayesian_inference/bayes_rule_applied.ipynb?source=post_page---------------------------)

## Code Training
- CodeWars (https://www.codewars.com/?language=python)
- Full Stack Deep Learning (design, train, deploy models) [[link]](https://fullstackdeeplearning.com/march2019)
- Learn Python 3 the Hard Way (Book)
- Coders at Work / Peter Seibel
- Computer Organization and Design / David Patterson and John Hennessy (how computers work from the ground up, important in understanding end to end)
- Automate the Boring Stuff
- Python [[review]](https://twitter.com/ryxcommar/status/1159241806506274816) [[link]](https://www.coursera.org/instructor/drchuck)
- Ranked and reviewed ML courses [[link]](https://twitter.com/chipro/status/1157772112876060672)
- 100 numpy exercises [[link]](https://github.com/rougier/numpy-100)

## Spatial Data science
- Spatial analysis tutorials in R [[link]](https://spatialanalysis.github.io/tutorials/)
Reproducible assignments with R-markdown [[link]](https://www.r-spatial.org/r/2017/04/13/assignments.html)
- Edzer Pebesma (SDSC 2019 workshop) [[link]](https://github.com/edzer)
- Spatial Dependencies [[link]](https://twitter.com/robinlovelace/status/1169200978245165059)
- Introduction to Spatial Data Programming with R (BGU) [[link]](http://132.72.155.230:3838/r/vectors.html)
- OpenGeoHub2019 [[link]](https://github.com/HannaMeyer/OpenGeoHub_2019/blob/master/slides/Practice_Hanna.pdf)
- The Bartlett Centre for Advanced Spatial Analysis [[link]](https://www.ucl.ac.uk/bartlett/casa/rspatial.org [[link]](https://rspatial.org/)
- Applied Spatial Data Analysis with R [[link]](https://asdar-book.org/)

## Statistics
- Caltech's probability distribution explorer (with Python code) [[link]](http://bois.caltech.edu/distribution_explorer/)


## Documentation
Make a Readme [[link]](https://www.makeareadme.com/)

## Math
- Solid guide to the math behind PCA [[link]](https://towardsdatascience.com/the-mathematics-behind-principal-component-analysis-fff2d7f4b643)

## The Job Search...
- *The* big list of DS interviewing resources [[link]](https://www.conordewey.com/blog/the-big-list-of-data-science-interview-resources/?utm_campaign=The%20Data%20Science%20Roundup&utm_medium=email&utm_source=Revue%20newsletter)
- ML interview (8k words, case studies, exercises) [[link]](https://github.com/chiphuyen/machine-learning-systems-design/blob/master/build/build1/consolidated.pdf?mkt_tok=eyJpIjoiWVdGaU4yTTNNek0xTnpFdyIsInQiOiJKeFwveWRic09uWjl4eW53Y21WTlY4ZHlPTlwvMkRZSXR4TmZ4cXJFXC9pXC9ENjgwWFwvZktUcFlKdFVtK1MrWXIxVzErZzhnU2FGYkhJanRVSSt0bWY1QlRIXC96bUU1NVJqcHB1bjgzcmljVWJRdlZtb1FzQzRnb3hLYjhGcWZLaUdsZSJ9&utm_campaign=The%20Data%20Science%20Roundup&utm_medium=email&utm_source=Revue%20newsletter)
- Great example of a DS technical + consulting question, with answers [[link]](https://twitter.com/colin_fraser/status/1199519328820850688)
- Cold emailing: short, clear about who you are, value prop for receiver, specific ask [[thread]](https://twitter.com/sriramk/status/1214278840358359040)
  - An example email [[link]](https://twitter.com/zebulgar/status/1200216090913071104)
- Great, actionable twitter thread with resources on preparing for algorithmic interviews [[link]](https://twitter.com/ASpittel/status/1214979863683174400)
- Questions to ask the interviewer(s):
  - How do data science decisions get made?
  - How is performance measured here?
- Questions to prepare for:
  - What’s your favorite machine learning algorithm? Alright, can you explain it to me?
  - You developed a new model that performs better than your old model currently in production. How do you determine whether you should switch the model in production? How do you go about it? Ans: Depends on how much the new model improved (on the biz problem, not necessarily the model metrics); would want to run in shadow mode for a while to test pipeline & dig more into results to verify no bias, bad results in specific categories, etc.
  -
- Use "from," "by," and "to" in resumes [[link]](https://www.inc.com/bill-murphy-jr/want-to-hire-best-look-for-these-3-key-words-on-every-single-resume.html)
- DS interview study guide [[link]](https://medium.com/better-programming/the-data-science-interview-study-guide-c3824cb76c2e)
- Example DS cover letter [[link]](https://www.dropbox.com/s/jw8x5qaww4jol91/Cover_Letter_Palantir.pdf?dl=0)
- Example DS resume [[link]](https://ilhamfp.com/files/ilham_firdausi_putra_cv.pdf)
- Emil W's story as a self-taught AI researcher [[link]](https://blog.floydhub.com/emils-story-as-a-self-taught-ai-researcher/)
- Twitter thread on what to learn when transitioning into data science [[link]](https://twitter.com/pip_alise/status/1222689361176813570)
- Explaining periods of unemployment: I took some time off to explore projects and am excited to get back to work.” then *move on*. [[link]](https://twitter.com/patio11/status/1224539020895514625)
- Be able to connect the machine learning model to the business impact. How to measure impact? Get familiar with key business metrics (revenue, profit, cost). [[link]](https://towardsdatascience.com/3-strategies-to-guarantee-a-data-science-job-with-no-experience-68d85b345f21)
- [[Twitter]](https://blog.twitter.com/en_us/topics/company/2019/engapprenticeshipprogram.html)
- [[ResumeSkills.us]](https://resumeskills.us/talent/shortage)
- Just use logistic/linear, decision trees [[link]](https://twitter.com/nihilistspicer/status/1151566718013255680)
- Science of the Job Search series [[talent.works]]
(https://talent.works/category/science-of-the-job-search/)
- How to ask good questions [[link]](https://jvns.ca/blog/good-questions/)
- Do you have time for a quick chat?
[[link]](https://medium.com/@treycausey/do-you-have-time-for-a-quick-chat-c3f7e46de89d)
- Emailing tips [[link]](https://twitter.com/vboykis/status/1162185666408648704?s=20)
  - Steps:
    1. Send a cold email to the recruiter (see "Direct Recruiter Email") and hiring manager
    2. Ramit Sethi's briefcase technique (also already downloaded). [[link]](https://towardsdatascience.com/3-strategies-to-guarantee-a-data-science-job-with-no-experience-68d85b345f21)

- if you're struggling to get a job with a title of "Data Scientist", consider looking at jobs that are frequently on the path to a Data Scientist role, like "Data Analyst".
- Example AI/ML consultant Linkedin [[link]](https://www.linkedin.com/in/yeehector)
- Just apply if you meet 30% of the requirements [[link]](https://twitter.com/jesslynnrose/status/1159034539227996160)
- Why blogs? "My blog was essential to establishing a career in the tech industry. When I had nothing to show on my resume, my blog demonstrated that I could understand and articulate technical concepts." [[link]](https://twitter.com/taravancil/status/1161087468172644352)
- Advice for graduates applying for data science jobs [[link]](https://mpopov.com/blog/advice-for-grads-entering-industry-datasci)
- Standing Out in a Sea of Data Scientists [[link]](https://towardsdatascience.com/standing-out-in-a-sea-of-data-scientists-c82e42a1e62b)
- How to Write a Great Data Science Resume [[link]](https://www.dataquest.io/blog/how-data-science-resume-cv/)
- Data helpers [[link]](https://www.datahelpers.org/)
- Columbia's interview prep [[link]](https://cdssatcu.com/interview-prep)
- Data Science and Machine Learning Career [[link]](https://github.com/firmai/data-science-career)
- LS Alumni Tips [[link]](https://github.com/nwthomas/lambda-school-alumni-tips/blob/master/tips/alumni-tips.md)
- Take home case study example [[link]](https://www.interviewqs.com/blog/case_study_example_1)
- Putting together a data science portfolio [[link]](https://www.youtube.com/watch?v=Zpdj50w0xKs)
- US data science job market [[link]](https://twitter.com/BecomingDataSci/status/1162387386514509830)
- Career advice regarding tools [[link]](https://www.johndcook.com/blog/2011/11/21/career-advice-regarding-tools/)
- Giving Some Tips For Data Science Interviews, After Interviewing 80 Candidates at Expedia [[link]](https://towardsdatascience.com/giving-some-tips-for-data-science-interviews-after-interviewing-60-candidates-at-expedia-395fff7e073b)
- whiteboard coding interviews [[link]](https://twitter.com/bria_sullivan/status/1171852539551199232)

>one of my favorite pieces of advice was from FastAI’s Jeremy Howard. He told me to focus on making one really great project that showed off my skills. He says that so many people have many interesting but half-finished projects on github, and that it’s much better to have a single one that is really polished. [[link]](https://hackernoon.com/how-not-to-do-fast-ai-or-any-ml-mooc-3d34a7e0ab8c)

- Projects don't get you jobs [[link]](https://towardsdatascience.com/sorry-projects-dont-get-you-jobs-3e5d8e74bfdc)
  - Intelligence testing: analytic thinking, variable extraction, edge case detection, process optimization
  - Projects are important for self-confidence, address variable extraction and optimization, get that initial call with a recruiter
  - After initial screenings, not really important
- Interview questions: [[link1]](https://twitter.com/djpardis/status/1205689645595381760)
  - This SQL one seems to be popular [[link]](https://t.co/p4aoh8JihA?amp=1)
  - Here is a 1-page data analysis in {R,Python,whatever}. Find and describe (a) one flaw in the code, (b) one flaw in the analysis method/parameters, and (c) one flaw in the conclusions drawn. (Because ability to debug predicts on-job performance better than ability to write code.)
  - A new airline, TJ Airlines, was started this year flying domestically in the US. A report came out that said TJ Air had the fastest boarding times of any airline. Tell me why that result is biased.
Follow up: design a better measure.
  - Ask what their favorite slack side/hobby channel is
  - for the next five minutes please explain to me a subject, any subject, that you’re really passionate about
  - You're a data scientist at a large telecom company that has contracted a large consulting firm to build a model to predict customer churn for wireless contracts. Overall customer churn is 6% per year, and we want to use the model to target likely churners with offers. Consultants train a logistic regression `churn2018 ~ csat + geography + total_revenue_2018` where churn2018 is binary = 1 iff the customer churned in 2018, csat is the most recent score on a customer satisfaction survey, geography is a factor variable for customer location. They report that their model has 94% accuracy. Your boss wants you to review their methods before we she pays the consultants. 1. What clarifying questions would you ask the consultants about their model? 2. Should we pay?
    - 27 ML exercises from huge doc on ML systems design [[link]](https://github.com/chiphuyen/machine-learning-systems-design/blob/master/build/build1/consolidated.pdf)

## Statistics
- Here’s my quick sketch of two very different ways to look at logistic regression [[link]](https://twitter.com/willkurt/status/1168880597877645312)
- Bayesian Data Analysis course material [[link]](https://github.com/avehtari/BDA_course_Aalto)
- Logistic or linear? Estimating causal effects of treatments on binary outcomes using regression analysis [[link]](https://psyarxiv.com/4gmbv)
- Logistic regression versus linear probability model [[link]](https://www.alexpghayes.com/blog/consistency-and-the-linear-probability-model/)
- FIT YOUR MODEL TO FAKE DATA! [[link]](https://twitter.com/polesasunder/status/1169616349313884160)
- Binary Dependent Variable? … Just use OLS [[link]](https://jeffbloem.wordpress.com/2019/09/06/binary-dependent-variable-just-use-ols/)
- Data Science Portofolios [[link]](https://twitter.com/BecomingDataSci/status/1177658356632358913)
- SQL portfolio projects [[link]](https://twitter.com/OmSteadily/status/1178153389747654658)

## Interesting
- dan luu's blog [[link]](https://danluu.com/)
Bayesian Re-Analysis Challenge (2019)
[[link]](https://docs.google.com/document/d/10g0l4H7uwf9S2g2Xv1y1VNj7vdGsk1UGtF7AgatzqgQ/edit#heading=h.om36m0top5c2)
- example of doing simple analysis on skewed data [[link]](https://mode.com/blog/demystify-skewed-data-and-deliver-analysis/?mkt_tok=eyJpIjoiT1RZeU1XWXlOems1TldSbSIsInQiOiJudU1HQURaNXh2RlJxT3l2eTVqcHZMbEpiamJYMDRlY3BBUFNxeFhWZ29cL3pER0lzRFBYZE9Tb1B3SjkwSW1hNDJVU0ZjR0RwUUE5eWlSZVhOWDgzRjEwZHQ2VEJNb0xNY3VQa3RiTEJlTndkS05DbkJSOG83VzVMTDJHY0dBYm0ifQ%3D%3D&utm_campaign=The%20Data%20Science%20Roundup&utm_medium=email&utm_source=Revue%20newsletter)
- linear or log regression with binary data? [[link]](https://statmodeling.stat.columbia.edu/2020/01/10/linear-or-logistic-regression-with-binary-outcomes/)
- Streamlit.io [[link]](https://streamlit.io/docs/tutorial/create_a_data_explorer_app.html) [[link2]](https://towardsdatascience.com/coding-ml-tools-like-you-code-ml-models-ddba3357eace) [[example1]](https://twitter.com/_inesmontani/status/1179155259819806721) [[example2]](https://twitter.com/_inesmontani/status/1179863682840498184)
- Data Tooling Market [[link]](https://medium.com/public-comps/data-tooling-market-2019-580e38b7475e)
- Pip vs. Conda [[link]](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)
- Pulling and wrangling tweets notebook! [[link]](https://nbviewer.jupyter.org/github/edsu/notebooks/blob/master/Languages.ipynb)
- numeric variables are like sliders, binary variables are like switches [[link]](https://twitter.com/andrewheiss/status/1171084259660107777)
- Data scientists need to know OOP. [[link]](https://twitter.com/ryxcommar/status/1174466337055412224)
- Data quality, data cleaning or data preparation stories [[link]](https://twitter.com/hugobowne/status/1164929866346749955)
- ML is about building web apps [[link]](https://twitter.com/vboykis/status/1180134944682717184)
- Missing data [[link]](https://towardsdatascience.com/explainability-of-missing-data-replacements-8eb164d68222)

> I like scikit-learn's consistent use of fit_transform and transform. It's nice to have a mental gap between "things I can do to the training data" and "things I can do to the test data".

# Moat Building
- Knowing the difference between inference and prediction; knowledge about research design (statistical bias, bad counterfactuals, measurement, generalization, validity); causality; statistics. [^f17592c2]
- Understand the business problem, go through data analysis, explain, show work via Github.[^33eac966]
- Be sure you know the handful of things that you can do better than most anyone else. Add something to that list every year. Make sure you can explain these things to non techies.[^f2f694c7]
- Be able to connect the machine learning model to the business impact. Think about what metrics the business uses to gauge the health of the business. Be able to communicate results in a usable way.
- Address things like: where to get the right data, how data can be bad and how to address that.
- Learn hierarchical bayesian inference models. [[example]](http://www.stat.columbia.edu/~gelman/research/published/lin.pdf)
- Keep the portfolio simple. Pick a dataset, ask questions and explore the dataset and see how many you can answer with simple data visualizations and summaries of the distributions of data. Build reports that indicate possible answers to your questions, and communicate your exploratory findings. Come up with a single "real world" question that you can answer with this dataset, as if a boss asked you a business question. This can be put in a resume (1-line explanation) and talk about in an interview.  

[^f2f694c7]: https://www.johndcook.com/blog/2011/11/21/career-advice-regarding-tools/

[^33eac966]: The pudding is great for this: https://twitter.com/vboykis/status/1162030016022175744

[^f17592c2]: https://twitter.com/dataandpolitics/status/1161319494049910784
