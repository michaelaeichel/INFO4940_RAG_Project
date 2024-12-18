# INFO4940_RAG_Project

Rag System Project Fall 2024

Notebooks:

simpletext_auto - dataset of 110 txt file documents from the Open access scientific technical and medical corpus

4940_Project_RAG.ipynb - Non fine-tuned RAG system. Chunks the OA STM documents for use in information retrieval, and combines IR query and input question prompt for text generation using LangChain framework.

Simple_Text_Generation.ipynb - Text generation to answer query questions. Does not have a RAG information retrieval component so does not use the OA STM data.

4940_Project_RAG_Finetuning.ipynb - Same RAG framework as 4940_Project_RAG.ipynb, but also contains my code for pre training the model on sets of 35 and 150 sample questions and answers.

txt_to_csv.ipynb - Converting txt format of sample Q & A for finetuning to csv for use by model

rag_finetuning_questions.csv - 36 hand written finetuning questions and answers for fine tuning

rag_finetuning_questions_large.csv - mix of 150 hand written and AI generated questions and answers for fine tuning
