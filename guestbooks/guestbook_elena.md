# ESL Article Acquisition

Ciao! You can find my project [here](https://github.com/Data-Science-for-Linguists-2019/ESL-Article-Acquisition). I have a few files in my exploratory data analysis folder, so if you want a quick and dirty explanation of what's what/where things are, you can go to my progress report [here](https://github.com/Data-Science-for-Linguists-2019/ESL-Article-Acquisition/blob/master/progress_report.md).

Edit: Sorry, I forgot I made some updates to the BALC_clean.ipynb file, which are clearly labeled. The updates aren't as polished as the rest of the file, just an FYI. You can poke around if you like, but I just wanted to give that warning.

Question: Why did the cowboy get a dachshund?

## Guest Entries:

### David’s entries

2019-03-07

#### What was done well

Terrific exploration of the text and image files! My first thought was to ask why we need the image files when we have the texts, and the preparatory explanation alerted me to the sort of scrutiny that both the text and images merit, and even require.

I know we’re supposed to mention only one thing that was done well, but the box and whisker plots in the BALC cleaning file are exactly the right visualization for the story they need to tell.

#### Area for improvement

Insofar as this was an interim report, and not just a peek at a work in progress, the cells at the bottom of BALC cleaning that generate errors or that haven’t been run might have been removed, or, at least, commented.

#### What I learned

This ties into what was done well: even though some of the work seems to have been done for us ahead of time (transcription, categorization, and—at least implicitly—finding and squashing duplication), and even though the project that published the data is fairly mature, we need to verify the data, and not trust it as received. For example, we didn’t check the ETS data for duplicates, and I would (unwisely) have extrapolated from that procedure and not checked BALC adequately.

__**Thank you so much for your comments, David! This was really good feedback. I did incorporate your comments for improvement and removed the error-generating cells and ran necessary cells before the second progress report. - Elena**__


### Cassie's Visit:
* **One Thing I Liked:** Good in depth look at your data and its
inconsistencies!Your code gives a clear outline of what your corpus
looks like and what flaws there are in its data. This makes the
motivation behind using /total/ totally clear! Also, really good use of
regular expressions to clean up your data!
* **One Area of Improvement:** What's your motivation behind your 3
hypotheses at the bottom of your project plan file? In your summary, you
briefly explain how articles work in Arabic, Spanish, and Korean, but
this might not make reasons for your hypotheses clear to readers,
especially people who aren't familiar with those languages.
* **One Thing I Learned:** At the bottom of your clean-up file, you use
something called SpellChecker from a package called spellchecker. I
didn't know there was a python package for that, but I'm not suprised
either. Ah, the wonders of python!

__**Thank you so much for your comments, Cassie! You're totally right, I made those hypotheses and didn't share an explicit and fully fleshed-out reasoning for them, and that may make it seem like a reach for those unfamiliar with the languages I chose. I will incorporate these moving forward! I meant to update this before the 2nd progress report, but forgot. - Elena**__

### Tingwei's Visit:
* **One Thing I Liked:** Your project has a lot of great ideas that I can use in mine. And I really like the way you did for data processing and analysis.

* **One Area of Improvement:** You can add more explanation to your data analysis to make it clear.

* **One Thing I Learned:** Many data processing method. I am really impressed by the regular expressions skill you have. There's a lot that I can learn.

__**Thank you so much for your comments, Tingwei! I definitely do need to expand on my analysis. I will make sure it's more fleshed out moving forward. - Elena**__


### Katie's Visit
- **What was done well:** You were very thorough with cleaning your data and making sure you catch everything! I'm definitely very impressed by how much of your time probably went towards the cleaning process!
- **What can be improved:** Everything looks really good so far! I might just work on creating a main file that contains the essentials from everything so that the reader can get a better understanding of the big picture. This could be something that doesn't need to be added until the end, though.
- **What I learned:** I learned a lot more about tagging words! This is an area that I'm not as familiar with so it was cool to see the different tagging methods you tried.

### Matt's Visit
- __What I liked:__ Well detailed explanations at the start of every notebook. Also good demonstration of knowledge on your subject material 
- __Area of improvement:__ Some of you code comments feel like they can be moved to markdown cells. I believe this would give your notebook a cleaner look in between your existing markdown cells.
- __What I learned:__ The existance of the spacy package in python, as well as a little on how to use it. 

### John's notes:
- *What I liked:* I really liked your analysis notebook. It was very 
thorough and seemed to cover a lot -- the breakdown of the varying 
languages and levels halfway through was a nice change of pace from 
following the code, as well as being super informative. Also, wonderful 
job with getting the articles!
- *What could be improved:* I'm not entirely sure how you'd do it, but 
it would be nice to see a leaner "get_articles" function. It works well 
for your purposes now, but it might take a long time to run in certain 
situations. 
- *What I learned:* How to make clean regex. I _really_ need to do that 
for my project...
