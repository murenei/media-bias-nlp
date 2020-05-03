# media-bias-nlp

[![Join the chat at https://gitter.im/media-bias-nlp/community](https://badges.gitter.im/media-bias-nlp/community.svg)](https://gitter.im/media-bias-nlp/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Investigation into political bias in media using NLP

# Overview
No specific goal as yet. Possible questions to answer (based on politician social media accounts rather than media orgs - the latter may be hard to obtain):

- what words predict partisan v. neutral messages?
- what words predict support messages v. attack messages?
- do politicians use Twitter and Facebook for different purposes? (e.g., Twitter for attack messages, Facebook for policy messages)?
https://www.kaggle.com/crowdflower/political-social-media-posts

Media bias. This website already does this. Maybe we can replicate it for AU?
https://www.allsides.com/media-bias/media-bias-ratings
https://www.kaggle.com/supratimhaldar/allsidescom-media-bias-ratings


Could also look at identifying fake news. Possible data set:
https://www.kaggle.com/mrisdal/fake-news

Depression prediction from social media?
https://www.kaggle.com/data/132022


# Draft Plan

1. Identify potential data sources
    - may need to curate a data source (scrape and then manually tag / use a tagging service at cost)
2. Investigate data
3. Basic NLP analysis
    - word frequencies
    - general sentiment 
    - topic modelling (using LDA)
4. Review ML approaches (sequence model, NN, simpler classification model)
5. Model
6. Hyper tune parameters
7. Publish on a medium blog or website or similar.

Need to be much more precise with the goals and methods. Look at other examples for inspiration.

# Potentially useful resources

https://www.kaggle.com/crowdflower/political-social-media-posts




