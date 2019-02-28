# To-do 10: Past Project Critiques

## Na-Rae the fake student
- Project 1: [Document Clustering](https://github.com/Data-Science-for-Linguists/Document_Clustering) by Dan Zheng
   - Strength: has a lot of code
   - Possible improvement: need more code
   - One thing I learned: providing [requirements.txt](https://github.com/Data-Science-for-Linguists/Document_Clustering/blob/master/requirements.txt) along with installation instruction for future guests was a great idea. It streamlines `pip` installation.  

- Project 2: some other project

## John the real student
- Project 1: [2016 Election Project](https://github.com/Data-Science-for-Linguists/2016-Election-Project)
	- Strength: Clean code, lots of good explanations (also super
detailed and organized analysis)
	- Improvement: Term "professional" unclear in presentation until
the end, would have liked more of the "process" in the presentation
	- Thing I learned: How to modify NER trees

- Project 2: [Dogs vs. Cat Neologisms on Twitter](https://github.com/Data-Science-for-Linguists/Dog_vs_Cat_Neologisms_on_Twitter)
	- Strength: Really interesting concept, fun presentation, clear
code
	- Improvement: Incorporating a way to read images (lots of memes
out there), is limited in what terms it uses
	- Thing I learned: More methods of handling Tweepy and DFs!

## Cassie the Metaphysical Student
- Project 1: [Dogs vs Cats on
Twitter](https://github.com/Data-Science-for-Linguists/Dog_vs_Cat_Neologisms_on_Twitter)
by Margaret Jones
	- Strength: The LIVE_data_collection jupyter notebook file is a
great way for people looking at her repo to get a good, hands-on way to
understand her project by letting them try out code themselves.
	- Improvement: Counting retweets and favorites seems more like a
general statistical analysis than a linguistic analysis. Is there a way
to focus more on the neologism trends? Also, since data was collected
over time, and trends varied based on when data was collected, it would
be interesting to see a time plot of retweet and favorite trends,
instead of just individual pie charts and bar graphs.
	- Thing I learned: Twitter can be really restrictive on scraping
data from tweets and publishing data! What tweets Twitter gives you
access to is an important consideration when doing any kind of twitter
analysis.

## Katie
- Project 1: [Dog vs. Cat Neologisms on Twitter](https://github.com/Data-Science-for-Linguists/Dog_vs_Cat_Neologisms_on_Twitter)
	- **What was done well?** This is such a fun idea! I bet the terms are even more popular now than when this project was done, it'd be interesting to take another look. Also, a lot of comments! This is helpful when reading through the code.
	- **What could be improved?** I think it's hard to compute things with tweepy since it is so limited. From my use of Twitter, I know favorites are more popular than retweets, but from this project, it was concluded there were more retweets. This intuitively doesn't make sense to me, so I think there is something more going on here.
	- **What did I learn?** There's a lot of numerical analysis here! This can be helpful if I need a refresher on creating graphs and other sorts of numerical data.

- Project 2: [Discourse Analysis of the Australian Radio Talkback](https://github.com/Data-Science-for-Linguists/Discourse-Analysis-ART-Corpus)
	- **What was done well?** Very clean code and pretty and intuitive graphs! I liked how everything was labeled so I didn't have to struggle to read through the code and figure out what each output corresponded to. This analysis seems very thorough.
	- **What could be improved?** When comparing groups of people, use statistical tests so we can see if the groups are actually significantly different. It would also be cool to compare the findings to an American talk show!
	- **What did I learn?** Australian talk shows are predominantly male, or at least the ones from this data sample. I also learned what back channels are, and thought it was really interesting how men produce more back channels when listening to men talk, and women produce more back channels when listening to women talk.

##Goldie
-Project 1:
-Project 2:


## Ting-Wei
- Project 1: [Document_Clustering](https://github.com/Data-Science-for-Linguists/Document_Clustering) by Dan Zheng
	- Strength: Handling really huge data - 12GB, Great idea to implement clustering method on wiki data classification. Clear explanation.
	- Improvement: For Hierarchical Clustering, it is hard to read the result. And the result seems to contain a lot of 'a' initial words.
	- Thing I learned: Real implementations on Tf-idf Vectors, K-Means and t-SNE method. Clear coding style.

- Project 2: [Native_and_Non-native_English](https://github.com/Data-Science-for-Linguists/Native_and_Non-native_English) by Katherine Kairis
	- Strength: Clear explanation for final report. Clear comparison
	- Improvement: The chart in 'trigram' part is not easy to understand.
	- Thing I learned: A lot of ideas for comparing native and non-native English.

## David

* Project 1: [Document_Clustering](https://github.com/Data-Science-for-Linguists/Document_Clustering) by Dan Zheng
	* **Strength:** Very clear exposition in presentation slides.
	* **Improvement:** It is unclear whether either single-layer or hierarchical clustering can provide the most useful perspective on the data. For example, a human might think that a resource (bookmark) is associated meaningfully, even if not equally, with more than one topic, and might want it to be in more than one category simultaneously, where the categories may not form a hierarchy. The two models explored here don’t seem designed to assign the same thing to more than one cluster other than hierarchically. Are there alternative models?
	* **Thing I learned:** How to approach the same core task with K-Means and Hierarchical clustering, and what the code looks like to perform the clustering.

## Elena

  - Project 1: [NYT_Figures_Sentiment_Analysis](https://github.com/Data-Science-for-Linguists/NYT_Figures_Sentiment_Analysis) by Christopher Lagunilla
    - **Strengths:** Super well organized, visualizations are easy to understand and aesthetically pleasing. Sentiment analysis includes four categories: "positive",  "negative", "neutral", and "composite".
    - **Improvements:** Maybe try the scikit learn NB classifier instead of NLTK? Also try and clean up the tokens a little bit more for the sentiment classification and training -- some of the features still included punctuation, which may have an effect on the sentiment classification. Also, may have been interesting to look at coverage of one or both of the persons of interest (e.g. Barack Obama) over time, to see how sentiment changed over a longer period of time.
    - **What I Learned:** How to read in and process XML files -- also learned about a sentiment analyzer (Vader)
