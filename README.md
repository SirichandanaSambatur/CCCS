# Comparing Corpora with Corpus Statistics

In this project, two psychology books from the gutenberg library have been chosen which are-

1) Dream Psychology: Psychoanalysis For Beginners By Prof. Dr. Sigmund Freud 
2) Ten Thousand Dreams Interpreted, Or, What’s in a dream. A scientific and practical exposition by Gustavus Hindman Miller

These two books that have been chosen are written about the same topic which is psychology behind dreams. Both these authors have a different perspective in this topic and hence, they have written their books using different approach where one discusses in depth about the reasoning and the other just interprets about what dreams mean. After the analysis of these two books, the following questions have been answered-

1) How unique are the two text files written by different authors on the same topic “Dream Psychology”?
2) Can the genre of the books be interpreted by the words that were being used by authors in their books?

The following are the folders/files present in this project are-

1) DreamPsychology- It consists of the book, all the files and files related to the book "Dream Psychology: Psychoanalysis For Beginners By Prof. Dr. Sigmund Freud"

2) TenTHousandDreamsInterpreted- It consists of the book, all the files and files related to the book "Ten Thousand Dreams Interpreted, Or, What’s in a dream. A scientific and practical exposition by Gustavus Hindman Miller"

3) Stopwords.txt- additional stopwords which help in analyzing this files in a better way and yeild better results.

4) Report.pdf- It contains the detailed analysis of the two books.

## Preprocessing Steps

1) Tokenization of the words from the books
2) Stop word removal
3) Using regular expressions to remove other non essential words like non-alphabetical words

## Analysis
The files have been analyzed based on the following statistics-

1) Frequency distribution of most common words
2) Bigrams
3) Trigrams

 The measures used for the analysis are pointwise mutual information and raw frequency.

## Running the project
Download all the files and open the "Comparing Corpora with Corpus Statistics.ipynb" file and run each of the cells.

## Software Requirements-

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [NLTK](http://www.nltk.org/)
- [Urllib](https://docs.python.org/3/library/urllib.html)
- [matplotlib](http://matplotlib.org/)

## Conclusion
Even though both these books are written in the same domain, each author has a different style of writing it and this result in the 92% of uniqueness among these two books. Also, because of this variation in the style and conceptual approach of writing, the book written by Dr. Sigmund Freud could be identified as a psychological book with 60% accuracy and on the other hand the accuracy of identifying the book written by Gustavus Hindman Miller is just 25%.

