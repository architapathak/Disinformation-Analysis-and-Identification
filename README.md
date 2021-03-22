# Disinformation-Analysis-and-Identification
Repository for data and code for the paper 'Disinformation - Identification and Analysis' : Winner of Disinformation Challenge at SBP-BRiMS 2020.

## Disinformation articles on the US Elections 2016
Articles are extracted from the following sources:

**Allcott, Hunt, and Matthew Gentzkow. 2017. "Social Media and Fake News in the 2016 Election." Journal of Economic Perspectives, 31 (2): 211-36.**

Link to dataset: https://www.openicpsr.org/openicpsr/project/113992/version/V1/view


**Kaggle Fake News Dataset**

Link to dataset: https://www.kaggle.com/mrisdal/fake-news


## Disinformation articles on COVID 2020

Articles are extracted from the following sources:


**EUvsDisinfo by EU StratCom Task Force**

Link: https://euvsdisinfo.eu/about/


**Newspunch - Identified as a popular fake news website by PolitiFact, FactCheck.org etc.**

Link: https://newspunch.com/

## Propaganda, Hoax and Satire Articles
These articles are extracted from the dataset provided with the 2017 EMNLP paper Truth of Varying Shades: Analyzing Language in Fake News and Political Fact-Checking

**Dataset Source:** https://hrashkin.github.io/factcheck.html

**Paper:** https://www.aclweb.org/anthology/D17-1317/

## Mainstream News Articles
Articles are extracted from:

**AllTheNews dataset**
Link to dataset: https://components.one/datasets/all-the-news-2-news-articles-dataset

## DNF-300 (DisiNFormation) Dataset Description
This dataset is created and used for degree of veracity prediction. The dataset contains 300 articles on the US elections 2016 with following fields:

**id**: Unique identifier of the article starting from 0.

**authors**: Authors of the article.

**headline**: Headline of the article.

**type**: (0) False; (1) Partial Truth; (2) Opinions Stated As Fact; (3) True ; (4) NEI

**urls**: Source/domain URL of the article.

**evidence**: URL of credible sources supporting or refuting the article. This field is empty when no evidence found which talked about the claims made in this article. 

![image](https://user-images.githubusercontent.com/25678184/110042612-087a9000-7d14-11eb-830c-6c674c5dff0e.png)
