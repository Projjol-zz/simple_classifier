## Simple text classifier using TextBlob

For this project I used the Naive Bayes classifier from TextBlob. I have assumed that the inout sentences would be short in length and grammatically simple. 

### Challenges

A challenge I faced was to handle random words. Given TextBlob as my dependency I felt it was to an extent a black box wherein 
I did not have too much control over the classifier. Possibly using NLTK directly would giv eme better results.

### Improvements

I would consider removing personal pronouns as they are adding an element of information to the classifier that does not seem useful. Looking at results returned by the informative_features method shows how the absence and presence of "I" divides greeting : studying and studying : bye in the ratio 2:1. Removing personal pronouns would let the the Naive Bayes classifier atune itself better to other words.