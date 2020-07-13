# Word_embeddings_BBC_News_archive
   The BBC news archive dataset contains about 2225 articles with their categories. The main objective is to build a neural net that predicts the category of the article. The stopwords from the sentences are removed and tokenized using the tensorflow library's Tokenizer and the sequences are padded and split into train and test and the neural net is fed with the training sentences and labels, the validation accuracy and loss is plotted. The model still needs hyperparameter tuning to be done as it can be seen that it is overfitting.
<div style="width:260px;max-width:100%;"><div style="height:0;padding-bottom:95.77%;position:relative;"><iframe width="260" height="249" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameBorder="0" src="https://imgflip.com/embed/484cxc"></iframe></div><p><a href="https://imgflip.com/gif/484cxc">via Imgflip</a></p></div>
This is the visualization of embeddings along with the labels. Which shows the neighbouring vectors for the word "dangerous" and it can be seen that similar words are clustered together.
