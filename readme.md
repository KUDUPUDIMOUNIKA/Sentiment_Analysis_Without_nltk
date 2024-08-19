cleaning text steps
1.create a text file
2.convert the letters into lower case(ex:APPLE->apple) 
3.remove punctuations like .,!? etc.(hi! this is build with python)

tokenisation=refers to the process of splitting the words in a sentence and grouping them in a list
stopwords=refers to the words which doesn't describe any emotion ex:i love,i doesn't have any emotion

nlp emotion algorithm
1) checks if the word in the final_words list is also present in the emotion.txt
   -open the emotion file
   -loop through each line and clear it
   -extract the word and emotion using split
2) if the word is present -> add the emotion to the emotion list
3) finally count the each emotion in the emotion list