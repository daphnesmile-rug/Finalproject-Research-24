# Finalproject-Research-24
Repository for the final project of research methods

# My Project

## General Information
This project analyzes the variation in average sentence length between the novels of Jane Austen and Arthur Conan Doyle. The focus of the project is how sentence structures reflect the different approaches to storytelling. The main goal of this research paper is to compare how the average sentence length varies between the authors and understand how this influences their writing styles and affects different audiences. We hypothesize that Austen’s novels use longer, more descriptive sentences that reflect her focus on social interactions and character development, while Doyle’s novels will contain shorter, action-driven sentences to maintain a fast-paced, action-oriented narrative. 

## Background Information
Sentence length reveals much about writing style and audience impact and helps understand how writing styles evolve over time. In research by Muchnik (2002), sentence length is proved to be an indicator of narrative style and pace, by examining sentence length in two novellas. Sentence length can differ significantly between works, which influences how readers experience and interpret the written text. In the research of Matthews, N., & Folivi, F. (2023) it is determined that shorter sentences improve readability and provide increasing accessibility and inclusion, which is also seen in fields such as public health communication. The findings highlight the importance of sentence length as a factor in determining how audiences process written material.
Rudnicka (2018) found sentence length has decreased over time over different genres, where this change is influenced by changes in society. Rudnicka also explains that sentence length varies widely between genres, reflecting differences in storytelling styles. These findings help in differentiating between short and long sentences in novels. Deveci (2019) identified that sentences containing around 20 words are optimal for comprehension. While this study focused on sentence length in research and educational texts, the threshold is will still be useful for analyzing sentence length in novels. We can apply this threshold to novels because understanding any type of text depends on how well readers can process the sentences and comprehend them. 

## Research Question and Hypotheses
Does sentence length reflect the different narrative and storytelling styles of Jane Austen and Arthur Conan Doyle?

Jane Austen's novels will contain longer sentences compared to Arthur Conan Doyle's novels. This will reflect the more elaborate and descriptive writing style of Austin, containing descriptive characters' thoughts, development, and social dynamics. To convey these details she uses longer, more elaborate and more complex descriptions, which will increase the length of the sentences. Doyle's style is designed for fast-readable detective stories, consisting of shorter, straightforward sentences that keep the action and the plot clear. Therefore, Austen's elaborate style will lead to longer sentences, while Doyle's action-focused writing is more concise and to the point.

## Method
**Dataset**
The dataset will include two novels from the authors, Jane Austin and Arthur Conan Doyle, which are retrieved from Project Gutenberg, an online archive of public domain texts.
The novels are:
* Jane Austin:
    Sense and Sensibility (1811)
    Pride and Prejudice (1813)
* Arthur Conan Doyle: 
    The Adventures of Sherlock Holmes (1892)
    The Hound of the Baskervilles (1902)

There are two variables included in the research:
* The dependent variable is the average number of words per sentence, categorized by short and long sentences. 
* The independent Variable is the Author, Jane Austen or Arthur Conan Doyle. 
**Sampling Method**
For sampling, the first 1000 sentences will be extracted from the text using a Python script, then words will be counted. Sentences are defined as text strings ending with punctuation marks, such as '.', '!' or '?'. Sentences between apostrophes ("") will not be considered as a separate sentence. Words are defined as text strings in sentences delimited by spaces: " ". Then depending on the average number of words per sentence, the sentences will be characterized as short or long. This data will be stored in a table as Table 1. Were the number of short and long sentences will be displayed per novel.
**Analysis Plan**
Python3 will be used for text processing, the extraction of sentences and words, and the counting of the words.

## Sources
* Culotta, A., N. R. Kumar, and J. Cutler (2015). Predicting the demographics of twitter users from website traffic data. In AAAI, pp. 72–78.
* Matthews, N. and F. Folivi (2023). Omit needless words: Sentence length perception. PloS one 18(2), e0282146.
* Muchnik, M. (2002). Sentence length in two novellas by judith katzir. Hebrew Studies 43, 7–20.
* Rudnicka, K. (2018). Variation of sentence length across time and genre: Influence on syntactic usage in English, pp. 219–240. John Benjamins Publishing Company.
