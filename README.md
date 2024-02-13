#  Corpus-SENT-COVID
This repository contains information from the project to identify sentiments and emotions in tweets related to COVID-19. The Polarity and Emotions corpora contain the same number of tweets.

# Corpus General Information

Initially, there were a total of 4,986 tweets from Mexico labeled as written in Spanish. Tweets in other languages were removed, reducing the corpus to 4,866 tweets. After removing the tweets with less than three words because of the difficulty in identifying sentiments/emotions in such short tweets, the final corpus consists of 4,799 tweets.

# :file_folder: General Information Labeling Corpus of Sentiments

The Sentiments corpus (<em>Labeling_Polarity.csv </em>) contains **4,799** tweets and the distribution by label is

| **Label** | **Number of Tweets** | **%** |
| -- | -- | -- |
| Neutral |   1,839   | 38% |
| Negative |  1,834   | 38% |
| Positive |  1,126   | 24% |
| Total | 4,799 | 100% |

##  :mag_right: Inter-Annotator Agreement (IAA)

The agreement between the three annotators was calculated using the Cohen-Kappa statistic to build the corpus. 

The results obtained are

| **Annotator Pair** | **Cohen’s $\kappa$ score** | **Agreement** |
| -- | -- | -- |
| A1 & A2 | 0.3945 | Moderate |
| A3 & A2 | 0.5547 | Acceptable |
| A3 & A1 | 0.3716 | Moderate |

Fleiss' Kappa statistic measure for the three annotators is **0.43697**.

# :file_folder: General Information Labeling Corpus of Emotions

The Emotions corpus (<em>Labeling_Emotion.csv </em>) contains **4,799** tweets and the distribution by label is

| **Label** | **Number of Tweets** | **%** |
| -- | -- | -- 
| Trust |   763   | 16% |
| Joy |  344   | 7% |
| Anticipation |  278   | 6% |
| Disgust | 328 | 7% |
| Anger | 878 | 18% |
| Fear | 129 | 3% |
| None | 835 | 17% |
| Surprise | 967 | 20% |
| Sadness | 277 | 6% |
| Total | 4,799| 100% |

##  :mag_right: Inter-Annotator Agreement (IAA)

The agreement among the three annotators was calculated using the Cohen-Kappa statistic to build the corpus. 

The results obtained are

| **Annotator Pair** | **Cohen’s $\kappa$ score** | **Agreement** |
| -- | -- | -- |
| Paola & Adriana | 0.6224 | Substantial |
| César & Adriana | 0.5294 | Acceptable |
| César & Paola | 0.6466 | Substantial |

Fleiss' Kappa statistic measure for the three annotators is **0.5979**.

# :pencil: How to cite

If you use the corpus, please cite the following articles:

# :neckbeard: Collaborators

- Helena Gómez Adorno, Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas - UNAM

# Aknowledgments
The work was partially supported by CONAHCYT project CF-2023-G-64 and UNAM-PAPIIT projects TA101722, IN104424...

