# Automate-Assessment-of-LD-Quality
This tool automates the rating of Linked Data Datasets based on the principles of 5 Stars of Linked Data Vocabulary Use. It comprises 3 modules:
1. RankUpto4Stars.py:
   It does all the processing required to rank an input model upto 4-Stars. The following are sub-functions of this module:-
       a. BuildVocabBase.py
       b. BuildDict.py
       c. FindBase.py
       d. LookUpResource.py
       e. CheckIfDuplicate.py
       f. TestLinksToVocab.py
       g. ProcessPattern.py
       h. CheckIfBase.py
       i. CheckIfInIgnoreVocabList.py
       
 2. ChkFor5StarCand.py:
    It identifies all the candidates of 5-Star datasets. The following is a sub-function of this module:-
       a. VBaseFunctions.py
       
 3.Rank5Stars.py:
    This updates the qualifying candidates' Star rating to 5 Stars and collates the information on the rest of them in descending order of rating. The following are sub-functions of this module:-
       a. UpdateRankedVocabs.py
       b. VBaseFunctions.py

In order to run this tool, all the 3 modules must be run in order. Also, the input and output file folders must be specified in RankUpto4Stars.py, ChkFor5StarCand.py as well as Rank5Stars.py
 
    
