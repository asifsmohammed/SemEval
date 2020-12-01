# SemEval
The goal of this project was to classify the semantic relation between a pair of entities in a sentence,
specifically the Cause-Effect, Instrument- Agency, Product-Producer, Content-Container, Entity-Origin, 
Entity-Destination, Component- Whole, Member-Collection, Message-Topic relations, as well as identify
the direction of the relation between the entities, i.e. whether the relation is from entity1 (e1) to 
entity2 (e2) or vice-versa or whether the relation is other, which is a special case that does not have
any direction. Different syntactic, lexical and contextual features had to be extracted in order to train 
models for the classification tasks.


Steps to run the project:


1. Open the .ipynb file in google colab
2. Run 1st cell and load all the files required i.e. semeval_train, semeval_test set, demo file and pre loaded features csv files (if available)
3. Import all the libraries in the next cell
4. If the features for the train and test sets are available directly go to step 7 or continue with step 5
5. Run cells in order to read data files and represent it in a dataframe
6. Run all the cells in task 2 in order (takes time to generate all the features)
7. Once the features are available, run all cells in task 3 and run the models (save pickle files if necessary)
8. For performance evaluation run cells in task 4
9. For demo upload a text file containing example sentence and relation (using first cell in notebook or using other possible ways in colab)
10. Run the cells in demo part to get predictions for given sentence


========================================================================


Libraries used:
1. Spacy
2. NLTK
3. sklearn
4. networkx
5. pandas
6. pickle
7. time
8. re
9. seaborn
10. matplotlib


========================================================================


Programming language:
Python 3
