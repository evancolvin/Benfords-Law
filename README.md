### Benfords-Law Repo

This is a repo for a project written in Python 2.7 that compares empirical data to Benford's Law.

We expect empirical data to *generally* follow a roughly log rule where the proportion of the first digits of the data follows P(d) = log(1 + 1/d) where the log is base 10 and d is the digit in question. This can be used in fraud detection because when people make up numbers they usually don't follow this pattern.

#### Goals:
Currently the library can take in a matrix of data and check the distribution of the first digits, but it could work better. Eventually, it will scan documents, ignoring dates and section headings, and comparing the digits to Benford's law. I also want to directly interface with Pandas data frames and other data formats.

I included an example, running the methods over the milk data set which is from Regression Analysis By Example, by Chatterjee and Hadi. The data is available [here](http://www1.aucegypt.edu/faculty/hadi/RABE5/Data5/P004.txt)

Here's a picture of what the output currently looks like:

![alt text](https://github.com/evancolvin/Benfords-Law/blob/master/benford_example.png)
