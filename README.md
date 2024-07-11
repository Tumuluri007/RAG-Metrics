Learnt about the 

RAG metrics
Also about Running the  RAG Metrics using LangChain and connecting to a vectorDatabase Called VectorDB.

Learnt about RAG metrics Such as:
1) Context Relevancy : Extracted revelant Sentences / Total senctences In context i.e (Query / VectorDatabase Context)
2) Context Recall: We give a set of Evaluation Questions and also a " Ground Truth Answers"
   Measure of Context Recall: GroundTruth Sentences attributed to Context / Statements In Ground Truth
3) Context Precision : Are Revelant Context are true Facts or not?
   Precision : True +ves / (True +ves + Flase +ves)
   Measure of Conext Precision : Sum of Precisions/ Total Relevant items in the Top K results

4) Faithfulness: Are the Answers Getting True or not.
5) Answers Revelancy : Generate a Question for the Given Answer.

 Flow Chart for Answer Revelancy.
 QUestion -> Answer Generated ( Low Answer Revelance) -> Asking Question to the Generated Answer -> Compute a Embedding for Generated Question -> Calculate Cosine Similarity or Cosine Score Between the Generated Questions and Orginial Question -> High Revelance Answer. 
