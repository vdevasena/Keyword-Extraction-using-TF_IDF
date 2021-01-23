# Keyword-Extraction-using-TF_IDF <br>

Extracting the relevant keywords instead of going thorugh the whole document/corpus using TF_IDF. <br>
Term Frequency - How frequency the word appears in the document. (The number of times the term t appears in the document). <br>
Inverse Document Frequency - How important a word is in a document. It is measured as log(total number of sentences / Number of sentences with term t) <br>

There are 6 simple steps to obtain top N keywords from the document. <br>
1. Document of Interest (get document or any sentences) <br>
2. Remove stopwords <br>
3. Term Frequency score <br>
4. Inverse Document Frequency score <br>
5. TF * IDF <br>
6. Get Top N Keywords based on the score <br>

