<h2>nlp-doc-classifier</h2>
<h5>Deep learning NLP document classifier with test document dataset</h5>
<ol>
<li>Dataset for train/test contains hashed values for each word in each document. The hashing function is unknown to the document classifer.</li>
<li>Since hashed words are used, a word vector model with pre-trained embeddings cannot be used (e.g. Glove, Spacy, Bert)</li>
<li>Embeddings are therefore trained as the model is trained</li>
<li>Tensorflow 2.0 Keras API is used for deep learning model development, training and testing</li>
<li>Two deep learning models are compared for the document classification:
<ul>
<li>3 layer separable CNN with Batch Normalization, dropout and L2 regularization</li>
<li>BiLSTM with dropout and L2 regularization
</ul></li>
<li>Both models achieved very good results and were verified with 5-fold cross validation</li>
<li>A test program notebook is also included for the separable CNN model that shows probablities for each class</li>
</ol>
