# ComRank
This code gives the implementation  of the paper "ComRank: Ranking Loss for Multi-Label Complementary Label Learning". 
 Requirements
- Python >=3.6
- PyTorch >=1.10

---
## Run:
**main.py**
- This is main function. After running, you will see a .csv file with the results saved in the directory.
The results will have seven columns: epoch number, training loss, hamming loss of test data, one error of test data,
coverage of test data, ranking loss of test data and average precision of test data.

## Specify the loss function argument:
- *args.lo=rank_exp_consis*: $\mathcal{\bar L}_\text{CR}$ 
## Specify the dataset argument:
- scene, scene_bia: scene dataset with uniform complementary labels and biased complementary labels
- yeast, yeast_bia: tmc2007 dataset with uniform complementary labels and biased complementary labels
