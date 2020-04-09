# Resume Scanner
Python program to detect how much a resume matches to the associated job description. 

# How To Use
Download the repository, replace my sample job description and resumes with your own. Then, run the program and you should see some simlarity scores.

# How It Works
The metric being used is cosine similarity. This is a metric used to determine how similar two documents are, irrespective of their size. In standard mathematics, this metric will measure the cosine of the angle between two vectors projected in a multi-dimensional space. In this scenario, the two "vectors" are actually two arrays containing the word counts of the two documents. Cosine similarity works well for this type of program because even though there is a disparity in size between the job description and the proposed resume, cosine similarity can still orientate them to be close together. As far as comparing these two documents go and giving a similarity score, the two documents are compared in numerous amount of fields such as text analysis, keyword count and usage in context, the subject being conveyed in the text, and several other factors. 

(Note: You can learn more about it here)
- https://www.sciencedirect.com/topics/computer-science/cosine-similarity
- https://www.machinelearningplus.com/nlp/cosine-similarity/
