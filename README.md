# A Comparison of Topic modeling methods : LDA, NMF, Top2Vec, BERTopic to Korean Twitter Posts on COVID-19 vaccine discourse.

# Dataset
Collect from Twitter using API (2022.08.17-08.18)
- Keywords : 노바백스, 모더나, 얀센, 아스트라제네카, 화이자
- Duration : 2021-02-01 ~ 2022-07-31

# Preprocessing
- [Common] 
Remove retweet, advertise, news, duplicate
Replace abbreviation
Correct spacing, grammer : py-hanspell [https://github.com/ssut/py-hanspell.git]

- [LDA, NMF]
Remove english, number, unknow characters


