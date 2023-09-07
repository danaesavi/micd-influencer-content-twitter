# Multimodal Influencer Content on Twitter
This repository is associated with the research paper titled [A Multimodal Analysis of Influencer Content on Twitter](https://arxiv.org/pdf/2309.03064.pdf)

D. Sanchez Villegas, C. Goanta and N. Aletras (2023). A Multimodal Analysis of Influencer Content on Twitter. AACL


__Data__

```data/``` this directory contains the Multimodal Influencer Content Dataset (MICD). It includes tweets from influencer accounts labeled as commercial or not commercial. For dataset statistics and more details please refer to the paper.

To comply with [Twitter's policy](https://developer.twitter.com/en/develop) (now X)  we share the tweet ID of each post. You can rehydrate (i.e. request the full Tweet) using the Twitter APIs. 

- data_key_mic.csv
- tweet_id: (int) the id of the given tweet
- domain: (str) the influencer domain that published the tweet (e.g., beauty, lifestyle,
- travel, fitness, food, tech, lifestyle).
- year: (int) year when the tweet was published
- month: (str )month when the tweet was published
- label: (int) binary label (commercial: 1/ not commercial: 0)
- split: (str) the split that it belongs to (train/dev/test) 

Tweets were retrieved in August 2021 via the Academic Twitter API. 
For research purposes you can contact us dsanchezvillegas1@sheffield.ac.uk





