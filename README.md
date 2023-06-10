# C4MTS-Task2-Baseline
This is the baseline code for C4MTS Task2.
=> Some issues that will be faced using this google colab are:
   1. RuntimeError: CUDA out of memory. The following command can be used to solve the issue :
      import torch
      torch.cuda.empty_cache()
      or 
      The runtime can be deleted and started again.
      Steps to clear delete and restart runtime:-
      1. Go to Runtime option 
      2. Disconnect and delete runtime
      3. Restart Runtime
   2. Switch to GPU can be done as follows
      1. Go to Runtime option
      2. Change Runtime type 
      3. Switch to GPU
   
