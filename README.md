# dogVcat
commit 1 : imported libraries and asked chat gpt about the use of 2 iblrares and i have described about my dataset structure .
commit 2:
    added new cell for splitting the dataset using imagedatagenerator and asked chatgpt regarding the above class in detail . 
commit 2.1:
    added info about imagedatagenerator using markdown and asked some more detalied questions about that like , constructor parameters
commit 2.11:
    added git ignore file in animals 
     https://chatgpt.com/c/67dc0db0-d698-8003-8b1e-3f5864ed50a8
commit 2.2:
    completely changed the code of splitting the data as we haven't used the augumentation , and the dataset size is only 1000 , 
    added sepearate splitting datagenerators for training and testing because testing don't need data augumentation.

commit 3:
    added .gitignore in checkpints
    added batch normalization in the import cell 
    trained the model on random architecutre and the validation accuracy was around 96 and i want to make many changes in that , just left that like how it was from the gpt , and i have also saved model for each epoch in a new checkpoints folder