# NLTK_Bible
Using NLTK to analyze word counts, frequencies in the Bible

The text format of the Bible is from : ('Gutenberg Project')[http://www.gutenberg.org/ebooks/10]

**Reading Local Files**
- need to use Python's built-in open() function, 
followed by the read() method. Suppose you have a file document.txt, 
you can load its contents like this:

>>> f = open('document.txt')
>>> raw = f.read()

open('document.txt', 'rU') — 'r' means to open the file for reading (the default), and 'U' stands for "Universal", 
which lets us ignore the different conventions used for marking newlines.
