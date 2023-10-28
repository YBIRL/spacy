# spacy

1) Run "create_DataTrain.py"
2) After running the process above you will see a file named "train.spacy"
3) Change "config.cfg" if required
4) In cmd run "python -m spacy train config.cfg --output ./output --paths.train ./train.spacy --paths.dev ./train.spacy" (note: config and training files should be in the same folder)
5) After training process you can see the results by running "test.py"
