# MSCAPP Seminar Lessons

On 13 Feb 2024, I gave a lunchtime talk on creating an analysis using basic text analytics and stylometrics. The [ISOT Fake News Data Set](https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/) was used as the basis for demonstrating the following activities:
- Setting up a text processing pipeline in [spaCy](https://spacy.io).
- Calculating counts and proportions of text features.
- Calculating readability metrics, vocabulary richness, and lexical diversity via common python packages:
  - Automated Readability Index (ARI) via [textstat](https://pypi.org/project/textstat/).
  - Type-Token Ratio and Measure of Textual Lexical Diversity via [lexicalrichness](https://pypi.org/project/lexicalrichness/).
- Determining emotion and valence of texts using [LeXmo](https://github.com/dinbav/LeXmo).
- Reviewed 3 potential projects using text analytics and stylometrics:
  - Clustering
  - Topic Modeling with BERTopic
  - Predictive Modeling
