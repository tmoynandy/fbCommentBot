# fbCommentBot
An attempt to train a comment bot to comment on social and current affairs issues.

Comments from NewYork Times article are extracted using this python package - https://github.com/AashitaK/nyt-comments 

Then a Markov chain model is trained on the NYT comments using python package markovify. To improve the sentence structure for the generated comments, high performance NLP package spaCy is used for parts of speech tagging and functions from the package markovify are overriden. 

Dependencies/ required python libraries :-
1. Pandas
2. markovify
3. spacy
