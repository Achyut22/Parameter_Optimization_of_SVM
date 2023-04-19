# Parameter-Optimization-of-SVM
## Sampling Assignment

*Dataset Used:* [Avila Data Set](https://archive.ics.uci.edu/ml/datasets/Avila)

| Number of Instances:  | 20867 |
|-----------------------|--------|
| Number of Attributes: | 10     |

## Attribute Information:

0: intercolumnar distance 
1: upper margin
2: lower margin
3: exploitation
4: row number
5: modular ratio
6: interlinear spacing
7: weight
8: peak number
9: modular ratio/ interlinear spacing
10 (Class): A, B, C, D, E, F, G, H, I, W, X, Y

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

![image](https://user-images.githubusercontent.com/79540598/233188115-3d94d198-cee5-44a0-9864-615f4e54c667.png)



## Submission by :
*Name* : Achyut Tiwari
<br>
*Roll No* : 102003640
<br>
*Subgroup* : 3CO25
