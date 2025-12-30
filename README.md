# The X Types - Mapping the Semantics of the Twitter Sphere

On the below URL you can find:

1. The full *dataset listing all the popular Twitter accounts and the corresponding knowledge base entries.
2. Model weights of the fine-tuned BERT used to produce the text embeddings.
3. Model weights of the neural network added on top of fine-tuned BERT, aimed at classifying an entities' semantic type based on textual and network evidence.
4. A full mapping of DBpedia ontology in an excel file.
5. A subset of the full dataset (1.) listing only the entities for which all popularity metrics are available (followers, pre-training corpus mentions and page-views. 

* Please note the dataset is not fully proccessed and cleaned (further filtering was done based on undisclosed information).
The current version is an initial product of alignment to knowledge bases, aimed at providing public information.

In this repository you can also find python file responsible for:
1. Integrating non-related features spaces in neural networks designed for multi-class classification (torch).
When used in our work to combine text and network user embeddings, it significantly enhanced the prediction quality.
2. Fine-tunning and predicting using BERT.
3. Mining tweets using Twitter (currently "X") public API - please note access was later disabled by Twitter.
4. Mining and querying semantic types from Dbpedia \ Wikidata databases.

Please feel free to write to: ogen.drukerman@gmail.com for any questions and clarifications.

Access (link can be shared for easy access):
https://drive.google.com/drive/folders/16LzZ_Upw0r9Sg00nCO0gnBPgzUU-SWBH?usp=sharing
