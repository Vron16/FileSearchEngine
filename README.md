# FileSearchEngine

The LittleSearchEngine class takes in several input documents and a final text file that contains the names of all the other documents. In addition, it includes a text file that has all the so-called "noise words" that will not be counted as keywords. 

First, the search engine includes all keywords from all documents and stores them in a hash table. A keyword is defined as any word in the documents that contains purely alphabetical characters except for the last characters, which may contain punctuation. The frequency at which each keyword appears in the document is also stored and each keyword is sorted in order of the documents it appears most frequently in. 

This data is then used in the top5search method, which retrieves the top 5 documents in which at least one of 2 input keywords appears in in order of highest to lowest frequency. In such a manner, the user will now be able to enter any word after supplying a set of input documents and see which documents the keywords appear in with highest frequency. 
