# Eva's Project: [Blog Sentiment Analysis](https://github.com/Data-Science-for-Linguists-2019/Blog-Sentiment-Analysis)
Welcome to my project! For more information about the project, check out [my project plan](https://github.com/Data-Science-for-Linguists-2019/Blog-Sentiment-Analysis/blob/master/project_plan.md). If you're interested in looking at some 2004 blogs, check out the [data_samples folder](https://github.com/Data-Science-for-Linguists-2019/Blog-Sentiment-Analysis/tree/master/data_samples).

Thanks for stopping by!
## h
### Elena's entries
#### 2019.03.07
 - *What was done well*: Your organization and writeup is really well-organized and easy to follow. The investigating you've done with the makeup of the corpus so far is pretty thorough, though I'm looking forward to see what else you'll add in the future! I think this is a really exciting project -- there's a lot that you can do with this, and you've set yourself up nicely here to go in a few different directions.
 - *What could be improved*: I think it would be interesting to look at the gender makeup of the different industries/ages, maybe as a consideration for the future (once you start doing the sentiment analysis). This might be especially pertinent if you're looking at usage of new lexis/linguistic trends, since women are often leaders of linguistic variation. It would be interesting to see if this is true in online language. Another consideration might be to look at the most common words used by gender (whether that's overall, by industry, by age, what have you).
 - *What I learned*: I'm surprised the makeup of bloggers actually skews slightly male! I wonder if that's across the board, or just for the source for this corpus?

 __*Thank you Elena! I tried incorporating the gender makeup of industries in my second progress report and I'm definitely going to continue to explore linguistic variation from that angle. - Eva*__

#### 2019.03.26
- *What was done well*: Again, your organization is fantastic, and your visualizations are easy to understand. I also really appreciate your comments about the topic clustering haha.
- *What could be improved*: When you do the original counter for words by industry -- why don't you try loading NLTK stop words as a variable straight in this step? You would be able to throw them out and try to re-visualize. I'm not sure if this would be faster or slower than using TF-IDF and count vectorizer, though.
- *What I learned*: I didn't know there was a Google Translate module in python! The more you know :)


### David’s entries

2019-03-07

#### What was done well

The organization of the data exploration, a combination of visual examination, statistical reporting, and plotting, is clear and effective. It made me think about the places where I trusted that my own data was what it purported to be, where I learned only later that it concealed unwelcome surprises that I could have avoided had I examined it more carefully at the beginning. The exploratory data analysis here is a solid example of how to do that.

#### What could be improved

Parsing XML with Python is always an adventure because none of the Python XML libraries has the full functionality available in languages that were designed to work with XML, like the most recent versions of XPath, XSLT, and XQuery. With that said, I would have liked to learn more about what it was about the data that made the XML difficult to manage in this case. That wouldn’t have improved the research (if someone has already converted the data to CSV and the CSV is easy to handle, it makes sense to use it), but it would have provided insight into what the specific issues were with the XML, and how they might be negotiated (otherwise than by avoiding XML entirely).

#### What I learned

We’ve practiced several ways to create charts and graphs so far, and the `.plot()` method used here is one of the simplest we’ve seen.

__*Thank you David! In the original XML files, each file was a blogger, and all of their blogs (for some bloggers, one blog, for others, a couple thousand) were stored in that file. I was having difficulty figuring out how to separate out individual blogs in each file and then recombine all of that data. In the future, I hope to learn more about handling XML files... but for now I'm very glad someone else did that for me. - Eva*__


### Cassies Entry (3/26/19)
- **What I Liked:** Great use of graphs for visualizations and
exploration!
Your code is easy to follow and illustrated well.
- **What Can Be Improved:** You mentioned this at the end of your second
ipynb file, but take out those url links if you can! Also, is there are
reason you've limited the number of words per topic? How could
increasing this number affect your results?
- **What I Learned:** Using Counter() for word frequency distributions,
and
LDA for topic detection.
Also, super interesting that astrological signs are included in this
data (even though this stat doesn't seem to have a huge impact on your
analysis)!

### Tingwei's Visit:
* **One Thing I Liked:** Your analysis is very clear with a lot of graph explanation. I like it. You also design many useful functions , that's great.

* **One Area of Improvement:** For the Blogger gender by industry chart, maybe you can adjust the color to meet the previous charts. Ex: blue for male, orange for female. That would be easier to read.

* **One Thing I Learned:** Many data analysis methods. There are a lot of plot function I can utilize in my project.

### Matt's Visit:
- __What I liked:__ I like the reactions to what shows up in the Topics from LDA. Diversity of graphs also gives a nice clean presentation.
- __Area of improvement:__ Looking into doing a table of contents. The ease of navigation really helps with development, and could come in handy if you do any presentation with the notebooks. Only drawback is that it doesn't work in GitHub's preview (to my knowledge anyway). 
- __What I learned:__ A little bit about how to use LDA in machine learning. Also a nice refresher on nltk's regular expression tokenizer.

### Patrick's Visit:
- __What I liked:__ I like all the visualizations you use. It really makes the jupyter notebook easy to follow and the data more easy it to understand.
- __Area of improvement:__ I think you might want to consider removing stopwords from the data you use. There seems to be only function words like the, of, and, etc. in your most frequent words for all topics, and these would probably be excluded if you use stop words. 
- __What I learned:__ Visualizing data and translating from other languages.
