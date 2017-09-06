Solution ranked 2nd in WalmartLabs ML Competition 2016

The following python libraries will need to be installed before the code can be run.

NLTK(Natural Language Toolkit) : http://www.nltk.org/install.html
Keras : https://github.com/fchollet/keras 

To install Keras, use the above link and check installation section on the website for further details regarding dependencies
required for Keras(Use Theano as backend since the code was tested on theano)

Theano: http://deeplearning.net/software/theano/install.html
bs4 library for BeautifulSoup


Running the code:
uncomment nltk.download() to first download the stopwords dictionary.
In the following lines: 
train = pd.DataFrame.from_csv('train.tsv', sep='\t')
test = pd.DataFrame.from_csv('test.tsv', sep='\t')
give the path to the train and test files.

The code should now run and generate tags.tsv as output file with the required labels.
