# dissertation
manage large source database
(1)Data.xlsx can be downloaded from https://liveuclac-my.sharepoint.com/:x:/g/personal/ucapwsh_ucl_ac_uk/EUpvoDXh35dNveUg9mJojIkB79pxDalGTCeWsfywW1yLig?e=EesIhU
Data.xlsx should be in the same file with word2vec.ipynb

(2) The link contains data extracted from Data.xlsx and crawled from the website
https://liveuclac-my.sharepoint.com/:t:/g/personal/ucapwsh_ucl_ac_uk/Ed9jzRxg_ZREulZYFF71MT4BWN5oqVoB82YtsR7cPy2WXA?e=LeyzAn
Please download data using this link and save the file train.txt into the same folder as abstract_classification.ipynb

(3) download the folder of glove.6B with the link https://liveuclac-my.sharepoint.com/:f:/g/personal/ucapwsh_ucl_ac_uk/EpRademE1ClLrVFPh41um20BPnWtAUI-JMstOFeklouhaA?e=rQVA0a and save the file into the same folder as abstract_classification.ipynb

(4) download the folder of glove.twitter.27B with the link https://liveuclac-my.sharepoint.com/:f:/g/personal/ucapwsh_ucl_ac_uk/EvLVEsRGImtDjCy3NiHJNHUBn70WoMdLgIdtb-IrsSlknQ?e=HSpGTD and save the file into the same folder as abstract_classification.ipynb

Finally, train.txt, glove.twitter.27B folder, glove.6B folder, and abstract_classification.ipynb should be in the same folder

word2vec.ipynb is the implementation of word2vec, abstract_classification.ipynb is for abstract classification, NER.ipynb is to extract named entity from the abstract, and TextRank.ipynb is to extract important sentences and noun chunks.

word2vec.ipynb and NER.ipynb need to work with GPU

install the following python package
| package | my version |
|-------|--------|
| nltk | 3.8.1 |
| sklearn | 1.2.2 |
| networkx | 3.1 |
| numpy | 1.23.5 |
| keras | 2.10.0 |
| pandas | 1.5.3 |
| spacy | 3.4.4 |
| gensim | 4.3.1 |
| torch | 1.12.1 |
| transformers | 4.30.2 |
| fasttext | 0.9.2 |

python -m spacy download en_core_web_sm

or

python3 -m spacy download en_core_web_sm
