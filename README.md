# QUORA
Identify which questions asked on Quora are duplicates of questions that have already been asked.  kaggle- https://www.kaggle.com/c/quora-question-pairs

Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.
The cost of a mis-classification can be very high.
No strict latency concerns.

Example Data point 
"id","qid1","qid2","question1","question2","is_duplicate"
"0","1","2","What is the step by step guide to invest in share market in india?","What is the step by step guide to invest in share market?","0"

Feature Generation using NLP and Fuzzy feature along with tfidf word representations.

ML models -SVM and XGboost
