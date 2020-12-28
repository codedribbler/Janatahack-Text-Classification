 Analytics Vidhya [Janatahack: Independence Day 2020 ML Hackathon](https://datahack.analyticsvidhya.com/contest/janatahack-independence-day-2020-ml-hackathon/ "").
 
 [Kaggle Notebook] (https://www.kaggle.com/wewake/multi-label-topic-classification-using-fastai)
# Topic Modeling for Research Articles using Fast AI.

### Hackathon Rank : 40 Private Leaderboard


## Problem Statement
Researchers have access to large online archives of scientific articles. As a consequence, finding relevant articles has become more difficult. Tagging or topic modelling provides a way to give token of identification to research articles which facilitates recommendation and search process. 

Given the abstract and titles for a set of research articles, predict the topics for each article included in the test set. 
Note that a research article can possibly have more than 1 topics. The research article abstracts are sourced from the following 6 topics: 

1. Computer Science

2. Mathematics

3. Physics

4. Statistics

5. Quantitative Biology

6. Quantitative Finance


## Train Dataset Schema


| ID               |  Unique ID for each article                             |
|------------------|---------------------------------------------------------|  
| TITLE            |  Title of the research article                          |
| ABSTRACT         |  Abstract of the research article                       |
| Computer Science |  Whether article belongs to topic computer science (1/0)|
| Physics          |  Whether article belongs to topic physics (1/0)         |
| Statistics       |  Whether article belongs to topic Statistics (1/0)      |
| Mathematics      |  Whether article belongs to topic Mathematics (1/0)     |
| Quantitative Biology     |  Whether article belongs to topic Quantitative Biology   (1/0)   |
| Quantitative Finance   |  Whether article belongs to topic Quantitative Finance  (1/0)    |



## Test Dataset Schema

                
| ID               |  Unique ID for each article                             |
|--------          |---------------                                          |
| TITLE            |  Title of the research article                          |
| ABSTRACT         |  Abstract of the research article                       |



```python
from fastai.text import *

```
