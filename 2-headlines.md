## News Headlines

### 1. Formating

[The Associated Press Stylebook](https://www.amazon.com/Associated-Press-Stylebook-2017-Briefing/dp/0465093043/) is a style guide widely used among American journalists. It enforces the following rules for capitalization of news headlines:

1. Capitalize nouns, pronouns, adjectives, verbs, adverbs, and subordinate conjunctions. If a word is hyphenated, every part of the word should be capitalized (e.g., "Self-Reflection" not "Self-reflection").
2. Capitalize the first and the last word in the headline.
3. Lowercase all other parts of speech: articles, coordinating conjunctions, prepositions, particles, interjections.

Write a program that formats a headline according to the rules above.

When done, run your program on [the corpus of headlines from The Examiner](examiner-headlines.txt) and submit your program and a file with corrected headlines. Output statistics: how many titles were properly formatted?

### 2. Catch catchy headlines

The paper on [Automatic Extraction of News Values from Headline Text](http://www.aclweb.org/anthology/E17-4007) defines that a catchy headline has the following features:
1. Prominence
2. Sentiment
3. Superlativeness
4. Proximity
5. Surprise
6. Uniqueness

For this task, write a program that analyzes a headline for prominence (use named entities without wikification), sentiment, and superlativeness. For sentiment, check if the average positive/negative sentiment for the top 5 meanings of word+POS in [SentiWordNet](http://sentiwordnet.isti.cnr.it/) is above 0.5.

When done, run your program on [the corpus of headlines](examiner-headlines.txt) and extract the headlines that have at least one of the described features. Submit your program and a file with catchy headlines.

### Additional notes

The data set was borrowed from https://www.kaggle.com/therohk/examine-the-examiner.

The easiest way to use SentiWordNet is through [nltk](http://www.nltk.org/howto/sentiwordnet.html). Writing your own parser will also work :)
