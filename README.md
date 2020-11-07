**Clustering**

**K-Means Clustering**

    - Dataset : Mall_Customers.csv
    - Clustering - understand patterns in the data
    - We are creating a dependent variable - class of customers
    - Out of the 5 features in the dataset,
        -  Customer ID - not needed
        - For visualization We limit to use only 
        - Annual Income (k$),Spending Score (1-100) 
    - Use Elbow method to determine the optimal number of Clusters - 5
    - To be safe from Random Initialization Trap, use init = kmeans++
    - Train the model and plot the clusters.
    
    - Business insight - Target on identifing what makes the CYAN cluster spend so less 
    - inspite of their high Annual income.

    - Also the GREEN Cluster can be made to spend more as they belong to high income.
    
    - Also be ethical and protect BLUE cluster by not tempting(ads) them spend more 
    - as they fall into a category with low income and high spending tendency
    
**Hierarchical Clustering**

    - Dataset : Mall_Customers.csv
    - Clustering - understand patterns in the data
    - We are creating a dependent variable - class of customers
    - Out of the 5 features in the dataset,
        -  Customer ID - not needed
        - For visualization We limit to use only 
        - Annual Income (k$),Spending Score (1-100) 
        
    - Plot Dendogram to determine the optimal number of Clusters - 5
    - Dendogram shows 3 Clusters also optimal.
   
    - Train the model and plot the clusters.
    - Train the model for 3 cluster also.
    
    - Same clusters hence Business insight as above.
      
      