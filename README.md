# Machine-Translation-to-SQL-Query
Uses an augmented CFG grammar to process natural language questions into SQL queries using the ATIS database. Has a seq2seq model with cross-attention and a seq2seq model with self-attention to predict the SQL queries.

Builds a semantic parsing system to convert English queries to SQL queries, so that by consulting a database the model will be able to answer those questions. Implements both a rule-based approach and an end-to-end sequence-to-sequence (seq2seq) approach. 

Goals \n

* Build a semantic parsing algorithm to convert text to SQL queries based on syntactic parse trees.

* Build an attention-based end-to-end seq2seq system to convert text to SQL.

* Improve the attention-based end-to-end seq2seq system with self-attention to convert text to SQL.
