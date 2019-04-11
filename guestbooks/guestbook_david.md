# Machine-assisted identification of rhyme in Russian verse

<https://github.com/Data-Science-for-Linguists-2019/russian_rhyme>

Здравствуйте, товарищи!

## Cassie's Visit
* **One Thing I Liked:** Your file annotations are great! Organized, and
so informative! You do a great job of explaining each step, acknowledging
any setbacks you may encounter, and outlining your goals for the future.
I especially like how you list the next steps of your project at the end
of your second project report notebook.
* **One Area of Improvement:** Your project's homepage has lots of
individual files by themselves, which can make navigating the homepage a
little confusing. Maybe you can consolidate some of these files into
folders?
* **One Thing I Learned:** The history of this corpus is so cool! And it
really shows just how difficult salvaging old data can be. Some of this
data could be reconstructed automatically, but other portions had to be
constructed manually. The amount of work David and his colleagues have
put into compiling this data is VERY impressive!


## Ting-Wei

* Strength: Complete data and nice data cleaning. Clear project explanation.
* Improvement: No matter the project report or progress report, they are all really complete. A lot of instruction to guide me. The only thing that I do not understand is how to pronounce Russian.
* Thing I learned: Basic Russian knowledge, ex: Phonetic and RhymeWord. The translation from Russian to English.

## Matt

- **One thing I liked** Use of codeblocks for displaying code. Well organized jupyter notebooks. Uses tools besides ones taught in class.
- **One area of improvement** : Repository Organization - could separate some files in the root to additional folders. Maybe some additional commenting on your non-jupyter python (just a little, I understand most of the documentation is found elsewhere, which you have linked).  
- **One thing I learned** : Learning to process XML with Python. Also, learning more about your corpus. Unfortunately, did not learn Russian.

## Patrick

- **Strengths** : I really like the project you are doing as I love Russian poetry. Your code is robust and well-written and pretty much checks all bases. I'm excited to see what the results will be.
- **Improvement** : You're missing a couple enclitics ("б", "ж", "ль") in your cyr2phon.py script. Also, I may be wrong but I think that your code currently only changes the idiosyncratic pronunciations (e.g. что, конечно, и т.п.) when they start a word (your code is {re.compile(r"\b" + key): value for key, value in lexical_data.items()}). If that's the case they won't match word internally, specifically I'm thinking of words like нечто/ничто (which aren't super common but ничто appears once in the first chapter of EO), нечестный, неизвестный. Nevertheless, these aren't really important mistakes for your purposes afaik, but they seem like they'd be easy to fix. Oh wait I was just thinking, I don't think your code accounts for ё being written without the diacritic, which might make rhymes between ё and о less obvious (e.g. ...был тонок and ребенок in Девушка пела... by Блок). This might be pretty hard to do though so you may have already considered it.
- **One thing I learned** : I honestly didn't even know that Python distinguished between private and public things nor that you could declare types of parameter and output in functions.

### John
- *What worked:* First off... holy crap! This project is incredible! As
a poetry lover, it's amazing to see the integrity of the poetics shine
through here. You did a really great job in guiding the reader through
your project. Makes a lot of sense to me.
- *What didn't:* I found it kind of challenging to work through your
repository. You're obviously working with a lot -- that being said,
clearer labels and groupings of your files would help orient both
yourself and the viewers to the desired information.
- *What I learned:* It's hard to pick just one thing! In general, I
really appreciate how inventive you were with using the various Python
functions to maniuplate your data. It's very detail-oriented and
inspires me to do better myself!

### Katie
- **What was done well:** There's a lot of good commenting and explaining! This seems like a huge project, and a lot of the code is unfamiliar to me. That being said, you make sure that the reader understands the goal and the process!
- **What can be improved:** It might be interesting to briefly mention how you think this same process would work on English words. Is Russian rhyme identification more difficult, about the same, etc.?
- **What I learned:** How to parse XML! I haven't had to use files in this format yet, so it's nice to see how it's done.

### Eva
- __What was done well:__ Your project idea is very cool! This seems like a really fantastic tool and resource for other linguists studying poetry, Russian or not. The organization throughout the project is great - it's very helpful to list out your files and directories in the readme.
- __Improvements and suggestions:__ I would love to see what you have done/are planning to do with this data! I visited http://poetry.obdurodon.org/ and learned a bit more on my own, but I think it might help readers to include more background on your research in the readme itself. This is just a question, not a suggestion - did you ever figure out how to use machine learning to assist with this project? I would be interested to learn more about how machine learning can be applied to this kind of analysis.
- __What I learned:__ Ok, so I technically didn't just learn this since you presented on it a couple weeks ago, but it's very cool to see the ways that you're using unit testing. It seems very useful, and I hope I can figure out how to use tests on my future projects.
