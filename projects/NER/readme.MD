Named entity recognition (NER) — sometimes referred to as entity chunking, extraction, or identification — is the task of identifying and categorizing key information (entities) in text. This game-changing NLP technique empowers machines not just to comprehend text but also to identify and categorize specific entities within it. 
<br />
Data is collected from kaggle which is Annotated Corpus for Named Entity Recognition corpus for entity classification with enhanced and popular features by Natural Language Processing applied to the data set.
The IOB Tagging system contains tags of the form:
<br />	B - {CHUNK_TYPE} – for the word in the Beginning chunk
<br />	I - {CHUNK_TYPE} – for words Inside the chunk
<br />	O – Outside any chunk
<br />The IOB tags are further classified into the following classes –
	<br />geo = Geographical Entity
	<br />org = Organization
	<br />per = Person
	<br />gpe = Geopolitical Entity
	<br />tim = Time indicator
	<br />art = Artifact
	<br />eve = Event
	<br />nat = Natural Phenomenon
<br />
<br />
RESULTS
<br />
The model is run over some of the test data of which some of the results are in the following figures. The model prediction on test dataset have an accuracy of 89.4%. This project on Named Entity Recognition (NER) exercises real life application of attention mechanism used in transformers by using it’s encoder block. Bidirectional Encoder Representations from Transformers (BERT) comes out to be excellent candidate for Named Entity Recognition(NER) applications.
![results](https://raw.githubusercontent.com/sachit3071/Machine-Learning/main/projects/NER/results.png)