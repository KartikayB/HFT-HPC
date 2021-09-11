# HFT-HPC
Parallel Computing on HFT
In Stock market, the traders with the fastest execution speeds are at greater profits than traders with slower execution speeds. Hence there is a dire need to optimize the algorithms to minimize the time of execution and to maximize the profits.



The project explores the domain of High Power Computation (HPC) using High Frequency Trading (HFT). With the application of parallel processing, we have parallelized the execution of multiple serial algorithms in order to achieve optimized execution time for training and finding whether a person should buy stock or not.



Attempts were made to minimize the training and prediction time. Multiple back ends like #algorithms Loky, Multi-threading etc. were examined and the results have been presented.

## About the files

- Background_Study :- All the experimentation done before finally reaching conclusion.
- HPC :- This folder consists of three folders  
      - Data :- The sample data used to train the basic models.  
      - Model :- The weights saved after final implementation of models serially.  
      - Model_Parallel :- The weights saved after final implementation of models parallely.  
- Final_Implementation.ipynb :- The final code with results in format of different graphs.
- Final_Implementation_Python_File.py :- Corresponding .py file.
 
