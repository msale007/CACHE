# Frequency Methods

The purpose of this folder was to test different approches for identifying the **most important tags** in the dataset.

Here are the list of methods implemented:


          * TextRank4zh package
      
          * RAKE (Rapid Authomatic Keyword Extraction)
          
          * Genism Library
      
          * TF-IDF
          
  
After compairing different methods, we found the ***TF-IDF*** method provided more consistent results, so we decided to use that method for extracting the highest rank keys in the text. 


Ultimately, we filtered the keys whose length was over 3 to provide more reasonable results.


Lastly, we tested the model on random JSON documents, and the results are shown in three different sections:


          * Words

          * Nouns

          * Verbs
