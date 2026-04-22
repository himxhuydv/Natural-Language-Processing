# Term Frequency - Inverse Document Frequency
a smart version of the bag of words model in this just dont't write the frequency vector but also tell the importance of the words,which words are important in this sentence/documents.
*Let's futher talk deepling into the TF -IDF*
## TF(Term Frequency)
Term frequency = how many times a words appears in a document.
same as the bag of words
**We write the vector frequency of appearning of that particular word in that whole sentences.**

## IDF(Inverse Document frequency)
we check the common across all document or rare 
IDF=log(total Document/Documents containing the word)

**Remember this thing**
* Words appear in many documents -> LOW Importance
* Words apear in few documents -> HIGH Importance
  **inshort word**
  TF increase-Low Importance 
  TF Decreases-High Importance