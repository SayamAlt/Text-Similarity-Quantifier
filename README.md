# Text-Similarity-Quantifier

## Objective

Establish an algorithm that can quantify the degree of similarity between the two text documents based on semantic similarity. 

Semantic Textual Similarity (STS) assesses the degree to which two sentences
are semantically equivalent to each other.
<ul>
  <li>1 means highly similar</li>
  <li>0 means highly dissimilar</li>
</ul>

## Technologies Used

<ul>
  <li>Python</li>
    <ol>
      <b><em>Libraries Used:</em></b>
      <li>Numpy</li>
      <li>Pandas</li>
      <li>Seaborn</li>
      <li>Matplotlib.pyplot</li>
      <li>Joblib</li>
      <li>warnings</li>
      <li>string</li>
      <li>Gensim Downloader</li>
      <li>Sklearn</li>
      <li>nltk</li>
      <li>math</li>
      <li>json</li>
      <li>requests</li>
    </ol>
  <li>Flask</li>
  <li>Machine Learning</li>
  <li>Natural Language Processing</li>
</ul>

## API Endpoint

The final algorithm should be exposed as a Server API Endpoint. In order to test this API, make sure you hit a request to the server to get the result as a response to the API. The request-response body should be in the following format:

Request body: {“text1”: ”nuclear body seeks new tech …....”, ”text2”: ”terror suspects face arrest ……”}
Response body: {“similarity score”: 0.2 }

Note: “text1”, “text2”, and “similarity score” keys should be kept as it is, without any change.

## Important aspect to consider

<p>The given dataset does not contain any label. Therefore, can be treated as an unsupervised learning problem. However, this does not imply that supervised techniques/algorithms are not applicable. The candidate is free to use any technique.</p>
 


