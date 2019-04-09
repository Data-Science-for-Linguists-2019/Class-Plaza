# Matt's Project - Have you Reddit? A Reddit Comment Analysis
Hello There! Welcome to my project! Come on in and learn about the tragedy of Darth Plagueis the Wise... er the details of my project.

* [My Project Repo](https://github.com/Data-Science-for-Linguists-2019/Reddit-Comment-Analysis)

## Guest Entries :

### Katie's post
- **What was done well?** I like the project idea! My project also includes some posts from Reddit (but not quite the same volume as yours!). I appreciate the dedication it takes to examine such a large corpus.
- **What can be improved?** I'd definitely give a summary of Reddit terms at the beginning, because I don't know what some of the columns are referring to. Also I think it would be cool to use machine learning to identify the subreddit, but that would be really difficult given the number of subreddits. Maybe something with just the top subreddits or something small!
- **One thing I learned:** I learned how to read in a huge data set in its compressed form, which is definitely very useful.

#### Matt's Response

Thank you for the response. I agree that I should limit the subreddits, I don't have a solid list yet. Also, I will try to put an explanation of subreddit terms into the final product.

### John's post
- *What was done well?*: Overall, great job! I think you walked us through your file modification really well. Also, I would be lying if I said I wasn't impressed by the sheer magnitude of data you've managed to acquire. I wish my files were like that!
- *What can be improved?*: Though I did appreciate your hypotheses in your project_plan.md file, I think you need to specify what you mean by "linguistic trends". Admittedly, I don't know very much about Reddit, but I do know that memes and very unique linguistic patterns profilerate quite rapidly. Perhaps you can see how the origin of a few particular patterns spread across subreddits? Right now, I'm not entirely sure what you're looking for.
- *One thing I learned*: The lzma.open function seems super helpful. Some corpora I've encountered use the .xz file extension and I may need to incorporate this module into a future project! Thanks!

#### Matt's Response

Glad you enjoy what you're seeing. I've moved on to mostly machine learning. I might do some linguistic analysis on the side, but it is no longer the primary aspect.

### John's second post
- *What was done well?*: Clean files with a good level of detail. Modifying your models as you went along really helped me follow your process. I think you're moving in the right direction!
- *What can be mproved?*: I'm not sure if your license is as thorough as it needs to be. Obviously, I'm not an expert on licenses, but what you have right now seems to be very informal and
unrefined. Perhaps look into this more?
- *One thing I learned*: The .isin function seems pretty interesting. It seems to simplifying functions quite a bit -- I'm defintiely going to check that out!

#### Matt's Response

Thanks for the second response, though I think you need to visit two further down the alphabetic list, not the same two people. Anyway, the license is indeed simple looking, but I talked with Na Rae. Apparently, for what I want, the setup I have right now works.

### Eva's post:
- **What was done well**: Helpful comments and explanation throughout your project. I really like the TOC in phase2_exploration.ipnyb. Nice job experimenting with machine learning! Considering the task, I think the accuracy scores you were getting were pretty good.
- **Improvements and suggestions**: Some of your data visualizations are a little small (and that one heatmap turned out kinda impossible to read). Increasing plot size and text size could make the plots easier to read. Might be also useful to use a monochromatic palette for the heatmaps. Currently, the data samples are too big to view on Github, so maybe create a really small data sample just so viewers who aren't necessarily planning on recreating your project can get an idea of what you're working with. One other small thing - there's a couple places in your progress report where the markdown isn't formatted correctly. Make sure to put a space after using a header marker.
- **What I learned**: I learned about some different ways to handle missing/messy data - good job on the data cleanup!

#### Matt's Response

Thanks for the feedback. I agree that I probably should make the heatmaps bigger. The reason the first heatmap, the one for all the subreddits, was not increased, was because the confusion matrix was gigantic, and I couldn't figure out how to render it properly without taking up too much space.

Also, thanks for the heads up on the markdown. My own markdown editor renders them as headers so I didn't catch it

### Cassie's entry:
- **What I Liked:** I love that you're including machine learning in this!
I can't wait to see how accurate you can get your classifiers to be! Also,
way to spend time in your data exploration code choosing
the
best way to store your data (which it looks like is SUPER important for your
project, since your data files are so big, and reloading it would be a
pain!). Finally, your jupyter notebooks have nice chunks of explanation and
analysis. Because of this, navigating your code is easy, the reasoning
behind your code is clear, and it was easy to interpret your results.
Overall, great job!
- **What Can Be Improved:** Your classifier in your preliminary machine
learning stage seemed to get messed up by the subreddit nba, maybe because
there were so many more entries for this category. When you split your data,
try
stratifying it, and see if you get better results! Also, right now your
progress reports have links to your code at the bottom of each report.
Embedding relevant links inside your summary next to the analysis it
corresponds to would make navigating your repo a little easier.
- **What I Learned:** I really like lzma.open! I'll have to remember this if
I ever want to analyze large compressed files!

### Elena's entry:
2019.04.02
- **What I Liked:** Your workflow and thought process is really easy to follow -- great use of markdown cells for explanation of what you're doing and your thought process. Also, the TOC in your current notebook is a great idea.
- **What Can Be Improved:** If it's possible, it might be a good idea to have a visualization of the breakdown of different subreddits going on in your project. If you're still having trouble picking subreddits, maybe limit your range so they have a decently close gap -- you have a lower limit, but not an upper one. Or you can try stratifying, like Cassie suggested.
- **What I Learned:** There's a normalize json function for pandas? That's really cool! That would have been useful for me a few weeks ago haha
