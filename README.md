# NLP-Google-like-search-engine
implement a Google-like search engine using a word2vec pretrained model using the following instructions:<br>
• Loading Data: Download 20 different documents in 5 different domains using<br>
Wikipedia API in python. Each document has to be at least one page (500 Words)<br>

• Download Model: Download a pretrained word2vec model. <br>

• Training: Use your pretrained model to create a word embedding for each word in each<br>
document then create a final embedding representation for each document using<br>
whatever method you want (Ex: Average). Then save the final representation for each<br>
document in a file on your hard disk.<br>

• Testing: Enable the user to enter any sentence in your search engine, generate its<br>
embedding then calculate the similarity between the sentence and all your documents<br>
using whatever similarity measure you want and the document embeddings you<br>
created. Then display your documents search results sorted descending based on their<br>
similarity to the input sentence (Exactly like google). <br>
