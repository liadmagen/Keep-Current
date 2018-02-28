## Objective:
To decide if a document should enter the aggregated user's document list

### Input:
- user's key interest topics
- user's historical document lists, and their feedbacks
- the parsed document
- relevance probabilities (outputs from the classifier)

### ouput:
- the probability of having the given document in the aggregated list



### How?
- consider using the [coritcal.io semantical folding](http://www.cortical.io/static/downloads/semantic-folding-theory-white-paper.pdf) approach for classifciation 