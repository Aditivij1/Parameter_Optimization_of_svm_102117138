# Parameter_Optimization_of_svm_102117138
Parameter optimization for SVM involves fine-tuning parameters like C (regularization strength) and kernel parameters to optimize model performance. Techniques like grid search or randomized search are used to find the best combination, enhancing SVM's accuracy and generalization on unseen data.

# Parameter-Optimization-of-SVM
## Sampling Assignment

**Dataset Used:** [Nursery Data Set](https://archive.ics.uci.edu/ml/datasets/nursery)

| Number of Instances:  | 12960 |
|-----------------------|--------|
| Number of Attributes: | 8     |

## Attribute Information:

parents: usual, pretentious, great_pret<br>
has_nurs: proper, less_proper, improper, critical, very_crit<br>
form: complete, completed, incomplete, foster<br>
children: 1, 2, 3, more<br>
housing: convenient, less_conv, critical<br>
finance: convenient, inconv<br>
social: non-prob, slightly_prob, problematic<br>
health: recommended, priority, not_recom<br>

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

The best parameters of SVC for the given dataset are:
- Kernel : rbf
- C : 6.393915  
- Aditi: 0.117114    

The above parameter gave a maximum accuracy of 0.9915.

### Convergence graph  : 
https://colab.research.google.com/drive/1TYCSMMh4dtZdgN400DXaYpbUbAjIpe7g#scrollTo=Vyyf9Jzr6ur6





## Submission by :
**Name** : Aditi Manmohan Vij
<br>
**Roll No** : 102117138

