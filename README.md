# My GradSchool_Projects

This repository is used to document some of my gradschool projects.

## Data Science Curriculum Design Using Clustering Analysis

The goal of the project is to design a course curriculum for a Master of 
Business and Management in Data Science and Artificial Intelligence program 
at the University of Toronto, covering all technical and business skills 
required for Data professionals

### Methodology
Hierarchical clustering algorithm was implemented to design this curriculum. 
Job posting information was web scraped from Indeed web portal. The logic was 
to cluster skills that appear together in most job postings, the rationale was 
that those courses are likely similar, and it makes sense to teach them together 
in the same course. For example, communication, presentation and leadership skills 
appeared together in most job postings

### Key Findings
Communication, presentation, leadership, python, sql, databases, machine learning and 
big data are the most in-demand skills. These skills and many others have been structured 
into course topics and sequenced according to prerequisites to design the course curriculum 
presented in the notebook.

### Skills Developed
Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA), Hierarchical Clustering 
Implementation and Analysis

## Linear Regression from Sratch Using Direct Solution and Gradient Descent

The goal of the project was to implement linear regression from scratch using a direct 
solution and full-batch gradient descent algorithm. The direct solution produced an RMSE 
value of **0.000172** on the test set while full batch gradient descent produced **0.000173**. 
Direct solution is known to be computationally expensive due to inverse computation hence 
gradient descent algorithm is preferred.

### Skills Developed
Implementation of mathematical formulas with Numpy

## Sentiment Analysis of Russia-Ukraine War

Russia’s invasion of Ukraine started in February 2022 and has been the biggest threat 
to international peace and security in the 21st century. The goal of this project is to gain 
insight into public opinion about the war, understand how Ukraine is viewed in the international 
scene and make recommendations to the Ukrainian government and international NGOs on strategies 
for modifying their campaign to gain support from a wider international audience

### Dataset
Tweets made on key events during the war was used for analysis. The events includes;

1. February 24, 2022:President Putin announced a 'special military operation' on eastern Ukraine
2. March 25, 2022:Russia announces the completion of their 1st stage of military operations and 
their primary focus was now on the 'liberation of Dondas'
3. April 6-7, 2022:President Biden administration prohibits US investment in Russia, calls for 
the expulsion of Russia from G20 and UN Human Rights Council
4. July 3-4, 2022:Russia claims to have taken Lysychansk, as it re-expands its goals to include 
other cities in Ukraine, marking the start of phase 3
5. August 24-25, 2022:Ukraine marks its day of independence from Soviet rule, which also marks 
the 6-month of Russia’s full-scale invasion

### Methodology
Data preparation was done using different functions from NLTK. A pre-trained VADER model was 
employed for sentiment classification. Keyword, N-grams and hashtag extractions, sentiment analysis 
and visualizations were developed using methods from sklearn such as NMF, TFIDF, CountVectorizer, 
Bag of words, etc and a suite of functions from NLTK such as SentimentIntensityAnalyzer(), 
word_tokenize(), RegexpTokenizer(), stopwords(), etc. Visualizations included piecharts, barcharts, 
wordclouds, line plots, etc.

### Key Findings
1. Predictions by the pre-trained VADER model revealed detail of both positive and negative sentiments 
of the general public to the war, as shown in section 4, Fig 1, **56.75%** of tweets were positive while 
**43.25%** were negative.

2. Widespread support for Ukraine: Much of the populace has a pro-Ukraine stance and is sympathetic to 
Ukraine’s cause and plight. Keywords such as ['friend', 'support', 'thank', 'people', 'slavaukraini', 
'standwithukraine'] reflect a positive attitude towards Ukraine and the way they have handled the situation. 
Word cloud visualizations of the hashtags from both negative and positive tweets in section 9, Fig 9 & 11 
reflect a high level of solidarity with Ukraine and deep condemnation and rejection of Russia’s invasion 
and massacre of innocent civilians in Ukraine. It contains phrases like #standwithukraine, #stoprussia, 
#stopputin and cities that have been invaded by the Russian military force such as #mariupol, #kharkhiv, 
#bucha, etc.

3. Fear of conflict expansion is mounting: One of the prominent results from the analysis has been the 
growing fear of a prolonged Russia-Ukraine war and its risk to the world. Based on topic extraction 
from the dataset using NMF in section 5 and negative hashtag extraction in section 9, Fig 10, keywords 
such as [''russiaukraine', 'russia', 'stop', 'wwiii', 'world', 'russiaukraineconflict', 'worldwar', 'putin', 
'war'] were identified, alluding to concerns that people’s own countries and lives are at risk. 

4. A sharp reduction in engagement: From the time-series plots in section 10, Fig 12 & 13, a sharp 
reduction in total tweets was observed between July and August. Also, although most tweets remain 
positive, they have reduced by more than 50% between July and August 2022. This can prove to be 
detrimental to Ukraine’s cause in the long-term.

### Recommendations
The Ukrainian government should put more effort into active monitoring of public opinions, swift 
denouncing of inflammatory claims and active engagement of international media. A data-defense 
strategy involving sentiment analysis could help Ukrainian officials and denounce inflammatory 
claims made to fuel escalating tensions. Keeping the international media informed and engaged 
with interviews and updates for strategic communications will also maintain public interest and 
eliminate misconceptions

### Skills Developed
Sentiment Analysis, Natural Language Processing (NLP), Analysis and Reporting of data-driven, 
evidence-based insights



