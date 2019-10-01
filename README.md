All explanations on setting up and running are in the "explanation.pdf" file.

What was added to the baseline:
-------------------------------

  - GRU swapped to BiLSTM

  - Corpuse embedings and question embedings were separated

  - Implemented BiDirAttention
  
  - Added a linear layer before "end" gate
 
 -----
 
  The final model is 
  
  
  ![model](https://github.com/Gregory06/SQuAD/blob/master/Imgs/model.png)
  
 -----
  
  Results
  -------
  
     dev/EM = 0.4617
     dev/F1 = 0.6088
     train/EM = 0.5720
     train/F1 = 0.7086
  
  ![model](https://github.com/Gregory06/SQuAD/blob/master/Imgs/results.png)
