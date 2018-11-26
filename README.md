# Create and Extract data and build Latent dirichlet allocation model to classify the documents.
* This is an advanced natural langauge processing project implemented from scratch. Python language is used to create the data.
* This project creates data by getting different pieces of data from a number of files majorly xml and txt data.
* The data used here is the meeting transcripts of the recorded data stored in a varierty of xml documents.
* The data is created and extracted by using the data_creation_extraction.ipnb file.
* The model is built in the topic_modelling.ipnb file.

* The generated data and the different file used to generate the data is present in a zipped folder.
* Different files and folder descriptions are as follow:

* words: Contains the words representations that can be used to generate the data.
* segments: Contains the segement breaks that can be used to end the pragraph while generating the data.
* topics: Contains the topics ids that can be used in generating the data.
* stopwords_en.txt: Stop words file used for the model.
* txt_files: Generated data using the python code for each text document is stored in this folder.
* data_creation_extraction.ipnb : used to extract the data from different files present in different folders.
* topic_modelling.ipnb : Build LDA model to classify the documents to different topics.

* Future work: More number of wrappers can be used to check if the coherence of the model can be improved. 
* Hierarchical dirichlet process can alos be used to checl if the coherence of the mdoel can be improved.

* Steps to reproduce the process:
* Unzip the zipped folder to any location on the local system.
* Download all the required packages, software and files.
* Run the jupyter notebook file data_creation_extraction.ipnb file. (Due to the large amount of data present, this step will take some time to execute)
* The above python file creates data files in the folder txt_files once it successfully finishes up the initial run.
* Run the jupyter notebook topic_modelling.ipnb file.
* It builds the LDA model and all the documents will be categorised accordingly.
