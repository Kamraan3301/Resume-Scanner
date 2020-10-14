<h1 align="center">Resume Scanner</h1> 

<p align="center">
A machine learning model to detect how much a resume matches to the associated job description.
</p>

## How It Works
The metric being used is cosine similarity. This is a metric used to determine how similar two documents are, irrespective of their size. In standard mathematics, this metric will measure the cosine of the angle between two vectors projected in a multi-dimensional space. In this scenario, the two "vectors" are actually two arrays containing the word counts of the two documents. Cosine similarity works well for this type of program because even though there is a disparity in size between the job description and the proposed resume, cosine similarity can still orientate them to be close together. As far as comparing these two documents go and giving a similarity score, the two documents are compared in numerous amount of fields such as text analysis, keyword count and usage in context, the subject being conveyed in the text, and several other factors. 

(Note: You can learn more about it here)
- https://www.sciencedirect.com/topics/computer-science/cosine-similarity
- https://www.machinelearningplus.com/nlp/cosine-similarity/

## Setup

#### Clone
```
git clone https://github.com/aahmad4/Resume-Scanner
```
#### Usage
```
cd Resume-Scanner
```
```
jupyter notebook
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
