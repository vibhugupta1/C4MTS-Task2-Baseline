# C4MTS-Task2-Baseline
This is the baseline code for C4MTS Task2.
=> How to use the code or google colab notebook.
   Step1 : There is an option on top when you open the code, "OPEN IN COLAB". This opens the file in the google colab.
   Step2 : If you are unable to exercise step1 then the .ipynb file can be downloaded and uploaded on google drive. Then
   you can open the file in google colab.
=> The train data and the test data should be uploaded on the google drive.
   1. The command "from google.colab import drive" "drive.mount('/content/drive/')" connects the colab notebook to the google drive.
   2. The command  "%mkdir /content/drive/MyDrive/myNewfolder" is used to make a new directory in the drive.
   3. The command  "%cd /content/drive/MyDrive" is used to change the current working directory to the filled path.
   4. To submit the results in the reuqired format, the code is given on how to write and make files "n.png". 
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
   
