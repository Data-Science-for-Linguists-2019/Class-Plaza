# Spell checker for second language  learner

#### Ting-Wei Shen

<https://github.com/Data-Science-for-Linguists-2019/Spell-Checker>

#### Matt
* __One Good Thing I liked__ : I like your project idea! The idea of creating a spellchecker is an interesting one to be sure, since it is relevant to today. Code is short and straight to the point as well.
* __One area of improvement__ : Your notebooks could use more markdown cells explaining what's going on. Your code is basic enough for now that it's easy to follow, but I foresee this being an issue when you construct a larger notebook for additional features of your project.
* __One thing I learned__ : I've learned an approach to filtering large samples of text using the re library in python.

#### Patrick 
- **One thing I liked** : I like the goal of the project, and the code/progress report are well written and easy to follow. Seperation of blocks of code in the jupyter notebook is well done and makes it clear what you are doing at each step, but perhaps you could add some comments/markdown cells.
- **One area of improvement** : There may be limitations on using more contemporary books, but they would probably be more useful since orthography may have changed from the 19th/early 20th century. Also, it may be better to use re.sub on '\n+' instead of just '\n' if you want to get rid of new line characters, since this will replace all new line characters in a row with a single space, rather than one space per newline character. You could also do something like [\r?\n]+ (i think this is the right syntax) which if I wrote it correctly, should match all of new line characters in a row, as well as new line characters separated by the carraige return character (all new line characters seem to be preceded by \r so you could maybe just use [\r\n]+). 
- **One thing I learned** : Using nltk plaintextcorpusreader to make df.

#### Katie
- **One thing I liked** : I like the idea! It's definitely different from a lot of the other projects. I also liked how you cleaned the data - it was easy to follow along with this process.
- **One area of improvement** : The ELI DataFrame is a little confusing to me. I think it would be beneficial to add some explanation as to where this came from and what the different columns mean. Also it would be cool to identify native language using machine learning, if you weren't planning on doing that already!
- **One thing I learned** : I thought it was cool how you eliminated the personal part of the data and flashed some of the rest of it! That was definitely a good idea for how to handle fair use.
