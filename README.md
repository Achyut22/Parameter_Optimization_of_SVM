# Parameter-Optimization-of-SVM
## Sampling Assignment

*Dataset Used:* [Avila Data Set](https://archive.ics.uci.edu/ml/datasets/Avila)

| Number of Instances:  | 20867 |
|-----------------------|--------|
| Number of Attributes: | 10     |

## Attribute Information:

F1: intercolumnar distance
F2: upper margin
F3: lower margin
F4: exploitation
F5: row number
F6: modular ratio
F7: interlinear spacing
F8: weight
F9: peak number
F10: modular ratio/ interlinear spacing
Class: A, B, C, D, E, F, G, H, I, W, X, Y

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
- Nu : 5.44 
- Epsilon : 0.68   

The above parameter gave a maximum accuracy of 0.78.

### Convergence graph  : 

![image](https://user-images.githubusercontent.com/79540598/233186045-1bdb6148-fa88-497c-a8c4-570c47ed5c3e.png)



## Submission by :
*Name* : Achyut Tiwari
<br>
*Roll No* : 102003640
