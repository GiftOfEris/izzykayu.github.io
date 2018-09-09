### Welcome to izzykayu's github homepage
I started learning Python :snake: in July 2017 and R in September 2017. But I coded a little bit a long, long time ago (I wanted my _myspace_ to look pretty). I'm always trying to learn more :sparkles: so any feedback is greatly appreciated! I'm diagnosed with four learning disabilities including dyslexia and ADHD, so if I can start coding--you definitely can. :sunny: Love of data science and tattoos :crystal_ball: Creative and Passionate. Pharmacy and Machine Learning. Futurist :green_heart: You can reach me at [isabel.metzger@nyumc.org](isabel.metzger@nyumc.org) or [linkedin](https://www.linkedin.com/in/isabelmetzger) or my newly made [twitter](https://twitter.com/diamondcrowbar):sparkles: or [quora](https://www.quora.com/profile/Isabel-Metzger-2):bust_in_silhouette:

:camera: instagram:[@datavizgirls](https://www.instagram.com/datavizgirls/)

I am passionate about machine learning methods to transform how we solve healthcare challenges. I am interested in taking advantage of these emerging technologies to improve how we understand patient health, predict outcomes, and target care. But not to stop at the collection of data, but to work towards implementation that can change lives.

### what I do now
I hold an MS in Biomedical Informatics from the Sackler Institute of New York University. During my master's thesis, I worked on deep learning models to predict Mortality from clinical text and have been contracted by New York Langone Health to build 2 month mortality machine-learning based models from initial history and physical notes of admitted patients. Specifically I work towards integrating a model into the hospital’s scalable text classification infrastructure that will emit model classifications at a performance threshold daily to an inpatient team for feedback. 

I also create hand-drawn and hand-painted gifs :woman_artist: 
![giph]<div style="width:100%;height:0;padding-bottom:75%;position:relative;"><iframe src="https://giphy.com/embed/VPJ4jqUVZenyE" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/train-VPJ4jqUVZenyE">via GIPHY</a></p>

### future plans
:sunrise_over_mountains: 

Continuing to learn as much as I can about machine learning and deep learning.

### what I did before

I earned a BS in Biochemistry, with minors in both Physics and Mathematics (and Studio Art), from ECSU. At ECSU, I served as the physics tutor and as a teaching assistant for courses in Biochemistry and General Chemistry and conducted research on carbon nanotubes and stress-defense in plants. At Pace University, where I began my undergraduate education, I worked at Haskins Laboratories researching cryptosporidiosis, a disease with devastating implications for the immunocompromised. After graduating, I spent time at Harvard University’s Nock Lab, where I completed a research assistantship studying suicidal behavior among senior adults and veterans. My experience serving as a member of a research team extends beyond university-affiliated groups: at Nalas Engineering Services, I proided research support on projects contracted by the Department of Defense.

Additionally, I completed one semester at the University of Maryland School of Pharmacy (UMSOP), ranked 9th in the nation. While I ultimately decided to withdraw, I managed to excel, placing in the top 25% of my class at the end of the semester.

### Some dataviz examples
>Heat map of CT Accidental Drug Deaths from 2012 - 2016
![Heat map of Accidental Drug Deaths from 2012 - 2016](calendar.png)

>Alluvial Time Series plot CT Drug Deaths
>Counts of Drugs Found in the Body at time of death
![Accidental Drug Deaths from 2012 - 2016](alluvts.png)

>Twitter Map using Google Maps Geolocation API
![IMAGE](mapwithcoveragelevel.png)

Last semester's term project with 4 predictive models:
>![Objective](heroinobjective.png) 

### So What did I query?
As someone who provides HCV/HIV testing and needle exchange services,
I wanted to follow a specific guideline and used the DSM-5 criteria for opioid use disorder:

>![Based off DSM-5](dsm.png) 
>![Code provided below](withdrawal.png)


#### TEAM PROJECTS:
team members: _Andy, Lee, Isabel Metzger_
1. [Identifying Adverse Drug Events from Clinical Discharge Summaries](https://github.com/izzykayu/n2c2TRACK2)

team members: _Mark Grivainis, Isabel Metzger_
1. [Among the Sleep] (https://github.com/izzykayu/AmongtheSleep)
_Time series physionet data to identify non-apnea sleep disturbances_ 

team members: _Isabel Metzger, Akshay T, Anupama Santhosh, Ethan Wu_
1. [A Natural Language Interface for Electronic Health Records](https://github.com/izzykayu/NaturalLanguageInterface)
_We built a natural language interface with the MIMIC III database using a seq2seq model for translation of natural language to SQL query_

team members: _Isabel Metzger, Julia Mahler, Teny Joseph, Nam Nguyen_
1. [Patient Quality Health Innovation Challenge]
_Twitter sentiment including my favorite form of expression (emojis) and chatbot creation_

team members: _Isabel Metzger, Lorel Burns, DDS, Ana Raghunath_
1. [Predicting tweeter’s state insurance coverage level via tweeter's profile text and tweet text](izzykayu.github.io/twitterdental.md)
2. [Exploring Dental Care Affordability via Twitter: A Descriptive Study](https://github.com/izzykayu/izzykayu.github.io/blob/master/DentalTweets/DentalCareAffordabilityViaTwitterPilot.pdf)

#### INDIVIDUAL PROJECTS:
1. [Identifying social media markers of substance abuse symptoms via tweets: Four predictive models](https://github.com/izzykayu/izzykayu.github.io/blob/master/herointweets/ML_4models_tweetanalysis_heroin_IzzyKayu.pdf)
2. [Supervised Learning predicting Heroin Death vs Non Heroin Death in CT Accidental Drug Related Deaths Government Dataset](https://github.com/izzykayu/izzykayu.github.io/blob/master/herointweets/DataStory_Short_IsabelMetzger_NYCDATAWEEK.pdf)

### PERSONAL PROJECTS:
1. DaniBot _(Chatbot based off my best friend Danielle because she is hilarious)_
2. Data Visualization of Tattoo Trends
3. Basketball Data Visualization #brooklynnets 

## Data Visualization and Exploratory Data Analysis
## REAL TALK: Opioids
Growing up in a working-class community where drugs offered comfort to many, I witnessed relatives and friends struggle with drug addiction, some until it killed them. By the time I turned 21, my uncle had died of Hepatitis C, contracted through needle sharing, and three of my friends had fatally overdosed on opiates. These losses forced me to confront the complexity of pharmacology at an early age—that drugs designed to maximize health often contribute to the undoing of vulnerable lives.

We as clinicians and health data scientists need to assume some responsibility for moving the field in a direction where clinicians are better trained to prevent and recognize drug abuse, and drug death, especially when working in resource-strapped communities. My community deserves this. **Every community deserves this.**

_This project uses multiple government open data sets_
1. **NATIONAL SNAPSHOT**: Glimpse of current US trends in opioid overdose death rates.
2. Machine Learning Prediction Model: heroin death vs accidental drug death with no heroin found in the body.
3. Additionally, I provide some analysis in trying to detect overprescribing of opioids.
### 1. NATIONAL SNAPSHOT
#### State Opioid Death Rates, adjusted for age and population.
![IMAGE](maps.png)
#### Change in Opioid Death Rates in States from 2013 - 2014. 
>When Opioid Deaths are adjusted for age and population, we can see that West Virginia currently has the highest rates of Opioid Overdose Deaths not only in the South, but for all states. In the Northeast, New Hampshire and Rhode Island have the highest Opioid Overdose Death Rates.
![IMAGE](BoxPlots_Year_Rates.png)

#### Opioid Death Rates by Year Compared with t-test p-values.
![IMAGE](ttest.png)
#### What states have significant Change in Opioid Death Rates? 
>Can we find novel ways in machine learning to save lives?
![IMAGE](OpioidDeathRatesboxplot.png)
#### Summary Statistics on US Regions and Opioid Death Rates
>Summary statistics of Death Rates for US regions in 3 years
![IMAGE](errorbarsplot.png)

**How I prepared the data and made these plots** :bar_chart: 
[pdf format](https://github.com/izzykayu/izzykayu.github.io/blob/master/national/graphsglimpse.pdf),
[rmarkdown file](https://github.com/izzykayu/izzykayu.github.io/blob/master/national/graphsglimpse.Rmd)

#### The poster from the showcase at NYU Open Data Week '18 Event held by BUGS Open Source :heart:
>Data-storytelling.
![IMAGE](PAU_Poster Portrait_OpenDataStory_FINAL_submit.potx.png)

**Sources:**
[CDC Drug Overdose Dataset](https://www.cdc.gov/drugoverdose/data/statedeaths.html)
[CT Accidental Drug Deaths Dataset](https://catalog.data.gov/dataset/accidental-drug-related-deaths-january-2012-sept-2015)
