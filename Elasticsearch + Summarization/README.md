## topic_modelling

Index each dataset separately in Elastic Search (one index for each dataset). <br />
Set up the indexes/types/fields in Kibana, then use an API to send all docs to the index. <br />
At the minimum you will need two fields: "doc_id", and "doc_text", you can add other fields. <br />
For DUC dataset add a field "gold_summary".c

Obtain Topic Models (K=10, 20, 50) for both datasets by running LDA (Latent Dirichlet Allocation) and NMF (Non-Negative Matrix Factorization) methods. <br />
For both LDA and NMF: print out for each topic the top 20 words (with probabilities) <br />

For LDA topics: <br />
-- ES: Add a type or new index "topic" with fields "topic_id" and "top_words" to store for each topic the top 10 words with associated probabilities.  <br />
-- ES: Add a field for documents "doc_topics" and update the index to store for each document the most important topics (up to 5) and doc-topic probabilities  <br />

## kl_summarization

Implement the KL-Sum summarization method for each dataset. <br />
Find the KL summary based on words_PD; PD is a distribution proportional to counts of words in document

