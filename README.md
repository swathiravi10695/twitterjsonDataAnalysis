# twitterjsonDataAnalysis

The dataset used for analysis can be downloaded from the following link <br>

 https://archive.org/download/archiveteam-twitter-stream-2019-08/twitter_stream_2019_09_30.tar


Uses the following modules: <br>

1. Python 3.7+ <br>
2. Pandas <br>
3. Regex Library <br>
4. NLTK Library <br>
5. PrettyTable <br> 
 <br>

 # Visualisations 

 Visualisations of the extracted data is performed by using Tableau.

# Preprocessing the Data using NLTK

Step 1: Extract the provided tar file by using an archive extractor <br>
Step 2: Proceed to extract the .bz2 files that are generated from each of the folders (00 to 23) by using an archive extractor.Open a jupyter notebook in the root directory './30' making sure that all the subdirectories are present in the same directory as the ipython notebook file. <br>
Step 3: Use python's OS module to walk through the current working directory and store the value of the jsons in a list. <br>
Step 4: Using str.lower() function convert text to lower case. <br>
Step 5: Using NLTK's TweetTokenizer package the extracted tweets are tokenised. <br>
Step 6:To remove the characters 'rt','via','...' ,create a remove_list containing these three elements and check if the string in original list is not present in the remove list. if it is present we don't add that to the new list. <br>
Step 7: Using str.isnumeric we remove the purely numeric from the list. <br>
Step 8: By utilising NLTK's Stopwords module we filter out the stopwords from the data set. <br>
Step 9: After all this is completed the preprocessing of the data is completed. We can now proceed to manipulate the data according to our need.<br>


# Screenshots