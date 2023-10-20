

NER_DEMO.ipunb notebook teaches us how to train and demos the inference of  Named Entity Recognition. It used the specifically prepared dataset for the training :

https://huggingface.co/datasets/conll2003

This is the cleaned and modified version of the original dataset, which is based on a scientific paper:

https://aclanthology.org/W03-0419.pdf

Thus, preparing datasets for training ML models is not a rudimentary task and requires extensive research work. 
The Regex-Token.ipunb  notebook demonstrates how a sample costume data set should be implemented ( the code is not totally true and the output either  ).

The test problem asks us to train the NER model on HTML extracted data from about 100 provided commercial URLs. The pars.ipunb notebook shows first steps in crawling a few of provided URLs. Parsing then MANUALLY tagging and tokenizing even one single URL for creating NER dataset for training the ML model requires some time and work, there are some straightforward methods which yields" Yet Another Crap AI Product". And there is a scientific search paper which guides how to prepare this dataset properly for training :

https://aclanthology.org/2020.coling-main.36.pdf


The owner could've sent us just some mock HTML files with a few lines to parse,  then w'd demonstrate with some straightforward parsing, manually tagging and tokenizing methods with further notation for the above research paper. BUT ! he sent us 600 full-scale URLs and asked us to prepare dataset from 100 of them within two days.
