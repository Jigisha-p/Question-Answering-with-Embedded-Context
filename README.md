# Text Embedding for Question and Answering

### Text Embedding:
The embedding process converts text to an N-dimensional vector

##### Use Cases:
- Search :  where results are ranked by relevance to a query string
- Clustering : where text strings are grouped by similarity
- Recommendations : Where items with related text strings are recommended
- Anomaly Detection : where outliers with little relatedness are identified
- Diversity Measurement: where similarity distributions are analysed
- Classification : where text strings are classified by their most similar label

### Project Description:
- In this project text embedding is used to convert a set of text information about start-ups into vectors.
- Then these vectors are used to add context to a query, assisting the completion model in answering a query.
- Document Similarity:
1. Embed a query string ro vectors
2. Perform a cosine similarity between query vector and all our document vectors.
3. Choose most similar and inject context
