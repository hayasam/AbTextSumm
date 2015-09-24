# TweetAbSumm
Abstractive Summarization: Code on the IJCAI paper

Please note that this code only tackles the summarization component and not the clustering part. 
The code takes a list of sentences, or a paragraph and produces an extractive or abstractive summary driven by the parameter "mode".

For language model:
Needs kenlm: https://kheafield.com/code/kenlm/ [See how to install]
Use any available ARPA format language model and convert to kenlm format as binary. KENLM is really fast. 

Other several packages required: PuLP for optimization, sklearn, nltk, cpattern, igraph
Best option is to use Anaconda package. All the above mentioned packages can be installed using pip.

A major part of the word graph generation code has been taken from https://github.com/boudinfl/takahe.

**If you use the code here, please cite this paper:**
_Banerjee, Siddhartha, Prasenjit Mitra, and Kazunari Sugiyama. "Multi-Document Abstractive Summarization Using ILP based Multi-Sentence Compression." Proceedings of the 24th International Joint Conference on Artificial Intelligence (IJCAI 2015), Buenos Aires, Argentina. 2015.
