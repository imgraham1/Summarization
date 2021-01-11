# Summarization

Read more on Medium: https://medium.com/@imgraham1996/exploring-a-different-approach-for-evaluating-summarization-methods-c6cefe28039e

Typically, summarization methods are evaluated based on the Rouge metric. This method uses assigns higher scores to summaries that have more overlapping words/n-grams in common with the original text. I believe that this evaluation fails to account for another one of the main purposes of summarization - to make the text more comprehendible for the reader. In this project, I implement 3 different summarization methods - extractive, abstractive, and a hybrid approach - and evaluate them not only using the Rouge metric, but also the level of improved readability.
<br><br>
I use the CNN/DM news article data set for this project which has been widely used in testing summarization techniques. 
<br><br> The results of this project show that the state-of-the-art pointer generator network proposed by See et.al. is the most effective method in creating summaries that contain the most information as well as effectively improve readability.
