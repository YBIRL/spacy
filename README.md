# spacy

1)In cmd run "pip install spacy" and "python -m spacy download ru_core_news_sm"

2) Run "create_DataTrain.py"
   
4) After running the process above you will see a file named "train.spacy"
   
6) Change "config.cfg" if required
   
8) In cmd run "python -m spacy train config.cfg --output ./output --paths.train ./train.spacy --paths.dev ./train.spacy" (note: config and training files should be in the same folder)
   
10) After training process you can see the results by running "test.py"
