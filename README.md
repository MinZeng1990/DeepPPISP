# DeepPPISP
PPI sites prediction through combining local and global features with deep neural networks

# Requirements

tensorflow==1.0.0

numpy==1.11.2

networkx==2.0

scikit-learn==0.18

gensim==0.13.3

# Usage

  In this GitHub project, we give a demo to show how it works. The three benchmark datasets are given, i.e., Dset_186, Dset_72 and PDBset_164.Dset_186 consists of 186 protein sequences with the resolution less than 3.0 Å with sequence homology less than 25%. Dset_72 and PDBset_164 were constructed as the same as Dset_186. Dset_72 has 72 protein sequences and PDBset_164 consists of 164 protein sequences. These protein sequences in the three benchmark datasets have been annotated. Thus, we have 422 different annotated protein sequences. We remove two protein sequences for they do not have PSSM file.
  
  The PSSMs, raw sequences, secondary structures and labels are given. You can split the raw three datasets by yourself. In our study, we use the 83% as training dataset (350 protein sequences) and 17% as testing dataset (70 protein sequence). The detail of the three datasets and dataset division can see the paper and the code.
  
  You can run the train.py file to train DeepPPISP and sue the predcit.py file to see the resluts.
 
# Citation

# License
This project is licensed under the MIT License - see the LICENSE.txt file for details
