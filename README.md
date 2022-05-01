#Group 1: Using Natural Language Processing to Determine Fake News

#Abstract
This Github hosts Group 1's work, research, and all of the significant  details and findings from the project of using NLP approaches to determine Fake News. Background discusses why Group 1 chose the topic of NLP. Purpose states the overall goal behind this project. Hypothesis states the general idea the group had before work began. Methodology shows all the different approaches the group used for the  project. Results shows the outcomes of all the approaches used. Conclusions states the summary of the project’s results and other points of interest.

#Background
NLP research seemed very interesting to get into. The group decided to dive deeper into Multinomial Naïve Bayes Model, used in spam research. As well as Count Vectorizer with N-Gram for auto competition when typing up a sentence. One of the last ones we did research upon was Linear Regression Model used in medical research. NLP is widely used in many real-world applications. 

#Purpose
The purpose of this project is to test different NLP models against one another to find a model that is optimal in determining fake news accuracy. 

#Hypothesis
Based off the group’s research, we hypothesize Linear Regression Model to yield the highest accuracy, while Count Vectorizer with N-Gram will yield this lowest. 

#Methodology
Each group member implemented, and tested a different NLP method. All of the models were tested with a common dataset to analyze common results. 

  Timothy Cantu: Long-Short-Term-Memory
  Samuel Hennon: Multinomial Naïve Bayes Model
  Zain Momin: Count Vectorizer with N-Gram
  Stephen Otten: TF-IDF Word Vectorizer with Passive Aggressive Classifier.
  Paul Perryman: Logistic Regression (TFIDF)

#Results
The results found that Logistic Regression (TFIDF) yielded the highest accuracy out of the five methods. This is due to the fact that libraries for python have become so advanced and efficient, implementation is quick. The lowest accuracy was Count Vectorizer with N-Gram because KNN is not the most efficient classifier due to try to find the nearest relationship neighbor. 

Table #1: Accuracy results of NLP Methods
![image](https://user-images.githubusercontent.com/70922160/166128552-7c26cc79-7e3b-440a-aac2-df8ea5435c06.png)

Figure #2: Confusion Matrix of Paul Perryman
![image](https://user-images.githubusercontent.com/70922160/166128560-5b190cee-9db7-4ed7-9c83-5c3eab23ffc1.png)


#Conclusion
-Multinomial Naïve Bayes Model trains the fastest but not as as accurate compared to the other models.  
-When using the unigram feature for N-gram is the best methodology.
-Training time took the longest for Long-Short-Term-Memory.
-Based off our findings we found NLP is a very broad field and new findings are coming up frequently.
-Further research is needed for each method to train and test the data further for better accuracy. 
