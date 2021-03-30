# Nltk -theory (Discussion of important Libaray)
# StopWord
The process of converting data to something a computer can understand is referred to as pre-processing. One of the major forms of pre-processing is to filter out useless data. In natural language processing, useless words (data), are referred to as stop words.
A stop word is a commonly used word (such as “the”, “a”, “an”, “in”) that a search engine has been programmed to ignore, both when indexing entries for searching and when retrieving them as the result of a search query.
*  import nltk
*  from nltk.corpus import stopwords
*  print(stopwords.words('english'))

# **word_tokenize()**
With the help of nltk.tokenize.word_tokenize() method, we are able to extract the tokens(part of letters e.g- "Iamaman"->"I" "am" "man") from string of characters by using tokenize.word_tokenize() method. It actually returns the syllables from a single word. A single word can contain one or two syllables.

# Tokenize 
A tokenizer that divides a string into substrings by splitting on the specified string (defined in subclasses)

# Stemming
Stemming is the process of producing morphological variants of a root/base word. Stemming programs are commonly referred to as stemming algorithms or stemmers. A stemming algorithm reduces the words “chocolates”, “chocolatey”, “choco” to the root word, “chocolate” and “retrieval”, “retrieved”, “retrieves” reduce to the stem “retrieve”. Stemming is an important part of the pipelining process in Natural language processing

# Porter’s Stemmer algorithm 
It is one of the most popular stemming methods proposed in 1980. It is based on the idea that the suffixes in the English language are made up of a combination of smaller and simpler suffixes. This stemmer is known for its speed and simplicity. The main applications of Porter Stemmer include data mining and Information retrieval. However, its applications are only limited to English words. Also, the group of stems is mapped on to the same stem and the output stem is not necessarily a meaningful word. The algorithms are fairly lengthy in nature and are known to be the oldest stemmer.

# Snowball Stemmer
It is a stemming algorithm which is also known as the Porter2 stemming algorithm as it is a better version of the Porter Stemmer since some issues of it were fixed in this stemmer.
*  Word           Stem
*  cared          care
*  university     univers
*  fairly         fair
*  easily         easili
*  singing        sing
*  sings          sing
*  sung           sung
*  singer         singer
*  sportingly     sport



