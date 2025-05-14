# Multimodal Fact-Checking and Explanation project  
This project solves the multimodal Fact-checking problem, which includes 3 subtasks: Claim Evidence retrieval, Claim verification, and Claim truthfulness explanation.  
The detail of the project is described as follows.   

## Dataset:  
The dataset used in this projects are:   
+ Mocheg: https://github.com/VT-NLP/Mocheg   
+ FACTIFY: https://github.com/Shreyashm16/Factify     

## Task 1: Multimodal Evidence Retrieval   
To be updated   

## Task 2: Multimodal Claim Verification 
How to run code: python task2/main .py <list_of_parameters>   
Parameters:    
 --batch size : number of batch size  
 --epoch  : number of epochs   
 --val : performing validation when training for each epoch (development set needed)    
 --path:  path to the training data   
 --claim_pt: pre-trained LM for claim encoding (BERT, RoBERTa)  
 --vision_pt: pre-trained LM for image encoding (ViT, DEiT, BEiT)  
 --long_pt: pre-trained LM for text evidence encoding (Longformer, BigBird)   
 --test: used for testing (without training)  
 --model_path  : path to saved model (used in testing phase).   
 --n_gpu:  number of GPUs (when having multiple GPUs)   

## Task 3: Multimodal Claim truthfulness Explanation 
How to run code: python task3/main .py <list_of_parameters>      
Parameters:    
 --batch size : number of batch size  
 --epoch  : number of epochs   
 --val : performing validation when training for each epoch (development set needed)    
 --path:  path to the training data   
 --gen_model: model for explanation (LED, T5, BART)    
 --test: used for testing (without training)  
 --model_path  : path to saved model (used in testing phase).
 --n_gpu:  number of GPUs (when having multiple GPUs)  
 
# Publication 
Luu, S.T., Vo, T. & Nguyen, LM. MCVE: multimodal claim verification and explanation framework for fact-checking system. Multimedia Systems 31, 242 (2025). 
https://doi.org/10.1007/s00530-025-01804-7

# Contributor 
Son Thanh Luu - Japan Advanced Institute of Science and Technology (JAIST)  
Trung Vo - Japan Advanced Institute of Science and Technology (JAIST)   
Prof. Minh Le Nguyen - Japan Advanced Institute of Science and Technology (JAIST) - Supervisor 
