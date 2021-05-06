# refactoring-metrics-prediction

Building ML models to predict refactoring classs with combinations of code metrics and commit messages as inputs. 

## Data Set used in this project:
For this project, commits from projects written in java, C, C++ are used. files are uploaded here. 
* commit_metrics.csv : file has code metrics and refactoring classes
* commit_text.csv: file has commit messages and refactoring classes
* commits_text_metrics.csv: file has commit messages, code metrics and refactoring classes 

## How to run the files from refactoring-metrics-prediction repository to generate results?

## Software Requirements
* Anaconda : Python 
* Text processing libraries 
* Keras
* Tensorflow


## How to install Anaconda?
* On Windows machine:
Follow the steps :

Install Anaconda on Windows 10(https://docs.anaconda.com/anaconda/install/windows/)

* On Mac machine :

Install Anaconda on Mac (https://docs.anaconda.com/anaconda/install/mac-os/)

**If you follow the similar steps given on above websites you will have different python editors in your system installed**


## How to install required text- processing libraries? 

* Run Python interpreter on Windows/ Linux / Mac
1. Enter the command 
  ```
  import nltk
  nltk.download ()
  ```
 2. Follow steps( https://www.guru99.com/download-install-nltk.html)
 3. Test if NLTK is installed properly on your system 
 ```
 from nltk.corpus import brown
 brown.words()
 
 ```
