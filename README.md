# Bigdata_assignment2

In the file named 'preprocess_final.ipynb' we have implymented the following functions :
1) clean_text(): it cleans the text by  
                    a) lowercasing all the words
                    b) removing special characters
                    c) punctuation removal
                    d) removing numbers
                    e) removing spaces
                    f) and removing stopwords
2) lancaster_lemmatize(): it applies lemmentization to remove the different forms of verbs
3) remove_non_english(): it uses snowball stemmer to remove all the non-english words
further in the file we drop rows which have same article_id and article_topic

second we have the file named 'code_final_part1.ipynb'  it has the following features:
1) forms the sorted vocabulary in alphabetical order
2) further it assigns indexes to the vocabulary

third file named 'code_final_part2.ipynb' it applies the following features
1) calculate_tf(): calculates the term frquency of each document indiviually
2) in the next block of code, idf is generated for each word
3) calculate_tf_idf(): finalizes the weightage by using tf and idf
4) this block uses different approach applied to find similarity between the query matrix and the matrix of each document
5) this uses the appraoch of scalar multiplication to find similarity but due to the lengthy process it keeps running and doesnt give any output.


