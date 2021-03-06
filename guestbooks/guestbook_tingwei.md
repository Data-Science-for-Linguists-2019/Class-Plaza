# Spell checker for second language  learner

#### Ting-Wei Shen

<https://github.com/Data-Science-for-Linguists-2019/Spell-Checker>

#### Matt
* __One Good Thing I liked__ : I like your project idea! The idea of creating a spellchecker is an interesting one to be sure, since it is relevant to today. Code is short and straight to the point as well.
* __One area of improvement__ : Your notebooks could use more markdown cells explaining what's going on. Your code is basic enough for now that it's easy to follow, but I foresee this being an issue when you construct a larger notebook for additional features of your project.
* __One thing I learned__ : I've learned an approach to filtering large samples of text using the re library in python.

#### Response
Thanks for your feedback! It's the preliminary project idea, and I will continue to revise it.

#### Patrick
- **One thing I liked** : I like the goal of the project, and the code/progress report are well written and easy to follow. Seperation of blocks of code in the jupyter notebook is well done and makes it clear what you are doing at each step, but perhaps you could add some comments/markdown cells.
- **One area of improvement** : There may be limitations on using more contemporary books, but they would probably be more useful since orthography may have changed from the 19th/early 20th century. Also, it may be better to use re.sub on '\n+' instead of just '\n' if you want to get rid of new line characters, since this will replace all new line characters in a row with a single space, rather than one space per newline character. You could also do something like [\r?\n]+ (i think this is the right syntax) which if I wrote it correctly, should match all of new line characters in a row, as well as new line characters separated by the carraige return character (all new line characters seem to be preceded by \r so you could maybe just use [\r\n]+).
- **One thing I learned** : Using nltk plaintextcorpusreader to make df.

#### Response
Thanks for your feedback! Your opinion is really useful for me. I will apply it to make my project better.

#### Katie
- **One thing I liked** : I like the idea! It's definitely different from a lot of the other projects. I also liked how you cleaned the data - it was easy to follow along with this process.
- **One area of improvement** : The ELI DataFrame is a little confusing to me. I think it would be beneficial to add some explanation as to where this came from and what the different columns mean. Also it would be cool to identify native language using machine learning, if you weren't planning on doing that already!
- **One thing I learned** : I thought it was cool how you eliminated the personal part of the data and flashed some of the rest of it! That was definitely a good idea for how to handle fair use.

#### Response
Thanks for the encouragement. I still have a lot of work to achieve my project goal.

### Eva
- __What was done well:__ Good explanations in your project plan and progress report! The data frames are well organized. The project topic is really cool and I'm excited to see your results.
- __Improvements and suggestions:__ It would be helpful to include more background on the ELI data. For the pie chart in your jupyter notebook showing token counts, consider making a legend. The labels will be easier to read in a separate legend. It also might be preferable to use a histogram or a density plot instead. After building your spell checker, you could try comparing your results with other spell checkers.
- __What I learned:__ Merging data frames! Definitely very useful.

#### John
- *What was good:* Your project is clean, easy to follow, and has a
clear goal.
- *What could be improved:* I could use a little more explanation on why
you chose your license. Also, the ELI DF is a bit confusing still.
- *What I learned:* .rename is a simple function to use, but I never
knew about it! I wish I had before...!

#### Cassie
- **What I Liked:** This is a very cool project! Understanding
and modifying a spell
checker is no easy feat! It's cool to see the limitations of Peter
Norvig's spellchecker. Also, your
project reports are very clear, and your ELI code has great dataframe
manipulation. You give good reasons for why you restrict your analysis
in the way you do (like restrictions on token counts and zooming into
certain L1's).
- **What Can Be Improved:** I think your jupyter notebooks could use a
little more annotation, to help readers follow what you're doing with
your data. (Though your annotations in your progress report 3 show a lot
of
improvement here!)
- **What I Learned:** Pie charts (and other visualizations)! I've been
struggling with how to
display my data, and after seeing your code, pie charts look like a good
idea!

#### Elena's visit
2019.04.11
- *What I liked:* You're using the ELI data too! Haha that's awesome. I think your entire project idea is really awesome. I could definitely use a spellchecker for some of my Arabic L1 data! I also like that you're investigating several different avenues for your analysis, including gender.
- *What Can Be Improved:* Consider comparing TTR and a different measure of lexical complexity. I talked to Alan, and went with Guiraud's R, which better controls for differences in text length. You divide types by the square root of total tokens.
- *What I Learned:* How to set up a pie chart. I probably should have chosen that for some of my visualization. Oops!
