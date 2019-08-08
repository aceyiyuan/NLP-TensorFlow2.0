# NLP-TensorFlow2.0

Part LDA (packages gensim, Ida)

Pre-processing Text

  - Tokenize, normalize(lowercase)
  - Stop word removal (not meaningful, want to remove. such as "is", "the")
  - Stemming (meet, meeting,met==>meet)
  
Convert tokenized documents to a document-term matrix (from which document has what words==>what words are occuring in whcih document)

Build LDA models on doc-term matrix
