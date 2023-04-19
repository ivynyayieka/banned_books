In this project, I analysed banned books across the world and within the United States. Even though the global database contained books starting from the 1300s, I limited my analysis to 1920 to 2020, a period for which I thought reporting of bans could be considered more reliable. <br />

# How I analysed the most banned books:
I checked the most frequently banned books by governments across the world. I highlighted every book banned by 3 governments or more in the treemap. <br />

# How I analysed the types of books most banned
For this, I used the types the dataset offered but also did an online search to fill in some of the unspecified titles. <br />

I also made the decision to cluster some of the titles to provide a summary that makes better sense for the audience. For instance, I grouped autobiographies, biographies and memoirs. But the column "type" still has the initial types before I clusterered them. <br />

I made the decision to split some types even though they could be put together. For instance, some poetry books could go under fiction.  Autobiographies could go under nonfiction. Some religious texts and political at the same time. Therefore, this section is a way to see an overview of the types but not the only perpective available <br />

# How I analysed the countries most banning books:
I checked the most frequently appearing governments. I highlighted top 5 governments. <br />
I excluded Indonesia in the top 5 even though it banned all Chinese literature. To make an analysis possible, I focused on case of specific book titles banned rather than generalisations <br />


# How I analysed number of books challenged in school districts in the United States as well as most challenged books

I compared 2021-2022 numbers of books challenged in different school districts to 2022-2023 numbers, but focused on the last full school year <br />

For most challenged books, I focused on the last full school year and selected top 5 most challenged books <br />

# How I analysed most common words in book titles:

I  calculated the most frequent words appearing in the book titles. I then realised that some of the frequent words included minor words such as "to" and "your". I considered cutting by length of word. However, some short words are significant, such as "joy". <br />

I therefore decided to create a database of minor words. <br />

I then removed minor words from the most frequently appearing words. I also removed the names of types of books eg novels, memoirs since those would appear in titles irregularly but yet I was interested in the main title not the type <br />

I presented the books whose titles appear more than 50 times. <br />

An alternative analysis would only look into the uniquely appearing words, so that the process analyses every unique title rather than all the titles in the data even as they reappear. <br />

I got a lot of support for this section from a previous analysis I did on [anthem lyrics](
https://ivynyayieka.github.io/anthems/)

You can see all the minor words I selected [here](https://github.com/ivynyayieka/anthems/blob/main/minor_words.csv)<br />

# Tech

Python, R, Adobe Illustrator, Datawrapper, Flourish, ai2html, D3, scrollama

# Sources
[Pronouns] (https://www.thefreedictionary.com/List-of-pronouns.htm)<br/>
[Articles] (https://7esl.com/english-articles/)<br/>
[Common Prepositions] (https://www.englishclub.com/grammar/prepositions-list.php)<br/>
[Conjunctions:] (https://englishgrammarhere.com/conjunctions/100-conjunction-words-definition-and-example-sentences/) <br/>
Basic verbs: handpicked eg. have, are, be <br/>
[Source of banned books in the world](https://en.wikipedia.org/wiki/List_of_books_banned_by_governments)<br/>
Source of books in the world: World Digital Library <br/>
[Source of most_frequently challenged books by decades](https://www.ala.org/advocacy/bbooks/frequentlychallengedbooks/top100)<br/>
[Source of censorship attacks](https://www.everylibraryinstitute.org/book_censorship_database_magnusson)<br/>
[Source of censored books in India](https://en.wikipedia.org/wiki/List_of_books_banned_in_India)<br/>
Other online searches for publication dates
