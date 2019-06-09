# FAQ_Bot
Simple FAQ handling chatbot that uses cosine similarity to match query with the text file to retrieve appropriate question token and give immediate next token, which is the result. It can handle basic salutations. An optional threshold can be set at around 0.5, either by simple trial and error or through a supervised ML algorithm. We can also provide an intermediate table, that matches query to access a bag of words which are likely to be in the answer token, that helps us retrieve answers even when user query isn't in the textfile. 
