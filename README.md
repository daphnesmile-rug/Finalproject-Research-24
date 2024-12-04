# Finalproject-Research-24
Repository for the final project of research methods

# My Project

## General Information
This Project analyzes the variation in average sentence length between the novels of Jane Austin and Arthur Conan Doyle. The foccus of the project is how the sentence structures reflect the different approaches in storytelling. The main goal of this research paper is to compare how the average sentence length varies between the authors and understand how this influences their writing styles and effects different audiences.


## Background Information
Sentence length is a meaningful linguistic feature, it helps understanding how writing styles evolve over time, and reflects cultural and literary norms.
It provides insight into how sentence length effects different audiences, sentence length can impact the readability and the reader's perception, and their appreciation for the literary works. 
These findings might assist in better understanding and appreciating these authors’ styles.
Studies have demonstrated the importance of sentence length in stylistic analysis. For example in research of Muchnik, M. (2002) the sentence length is proved to be a indicator of narrative style and pace, by examining sentece length in two novellas. Sentence length can differ significantly between works, which influences how readers experience and interpret the written text. 
In research of Matthews, N., & Folivi, F. (2023) it is emhasized that shorter sentences improve readability and promote social justice by increasing accessibility and inclusion, which is seen in fields such as public health communication. The findings highlight the importance of sentence length as a factor in determining how audiences process written material.


## Research Question and Hypotheses
How does the average sentence length differ between Jane Austen's novels and Arthur Conan Doyle's novels, and what might this tell us about their unique writing styles and intended audiences?

Jane Austen's novels will contain longer sentences compared to Arthur Conan Doyle's novels, reflecting the more elaborate and descriptive writing style, containing descriptive characters' thoughts and social dynamics. She uses complex sentence structures consisting of multiple parts to convey these details. Doyle's style is designed for fast-readable detective stories, consisting of shorter, straightforward sentences that keep action and the plot clear. Therefore, Austen's elaborate style will lead to longer sentences, while Doyle's action-focused approach is more concise and to the point.


## Method
**Dataset**
The dataset will inclode two novels from the authors, Jane Austin and Arthur Conan Doyle, which are retrieved from Project Gutenberg, a online archive of public domain texts.
The novels are:
Jane Austin:
    Sense and Sensibility (1811)
    Pride and Prejudice (1813)
Arthur Conan Doyle: 
    The Adventures of Sherlock Holmes (1892)
    The Hound of the Baskervilles (1902)
**Sampling Method**
For sampling, sentences will be extracted from the text using a Python3 script, then words will be counted. Sentences are defined as text strings ending with punctuation marks, such as '.', '!' or '?'. Sentences between apostrophes ("") will not be considered as a separate sentence. Words are defined as text strings in sentences delimeted by spaces: " ".
The size of the sample will be a random sampling of 1000 sentences of each novel.
**Analysis Plan**
Python3 will be used for text processing, the extraction of senteces and words and the counting of the words.

## Sources
Muchnik, M. (2002). SENTENCE LENGTH IN TWO NOVELLAS BY JUDITH KATZIR. Hebrew Studies, 43, 7–20. http://www.jstor.org/stable/27913589

Matthews, N., & Folivi, F. (2023). Omit needless words: Sentence length perception. PloS One, 18(2), e0282146. https://doi.org/10.1371/journal.pone.0282146