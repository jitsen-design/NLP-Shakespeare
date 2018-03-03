# NLP in Five Acts

NLP in Five Acts is a project which tries to validate some characteristics of Shakespearean comedies and tragedies. Comedies typically have the following characteristics:

* A struggle of young lovers: Element of separation and reunification
* Mistaken identities, often involving disguise
* The intelligent servant/clown
* Family tensions
* Complex, interwoven plot-lines

Tragedies tend to have the following attributes:

* Social breakdown and isolation of characters
* Death
* Inevitability
* Central flawed figure

The five notebooks in this document explore these characteristics:

1. Shakespeare-Viz 
   
   Visualize the spread of three corpora at a time, using Word2Vec. The tragedies seem to have stronger gravitational centers, compared to the comedies.

2. Shakespeare_NMF_T-SNE
   
   Attempt to identify dispesion of topics for a given corpus. First each word is assigned to the highest probability topic using NMF (Non-negative Matirx Factorization). Then words are plotted in space using Word2Vec. Finally, colors are assigned to each word based on initial assignment to topic, and plotted using TSNE. Exercise did not show promising results.

   A second attempt using a stripped-down corpus (words with frequency of 1 only) did not produce satisfactory results either.

3. Shakespeare_Topic_Modeling

   Attempt to look at distinct topics for a given corpus. Once again, model failed to separate topics coherently

4. Shakespeare_Polarity

   Conduct sentiment analysis on plays and characters separately. In general, as expected, antagonists and tragedies have lower polarity, although model cannot make accurate inferences on word-play.

5. Shakespeare_Most_Similar

   Find most similar words to a word in a given corpus, and return sentiment for word.


  

