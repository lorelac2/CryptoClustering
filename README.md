# CryptoClustering

## Analysis 
The purpose of this analysis is to use unsupervised learning models to predict if cryptocurrencies are affected by 24 hour or 7 day price changes. The dataset was comprised of 41 cryptocurrencies with 7 timestamps of varying ranges. Inertia was used to find the best K value in order to cluster the data and then plot it. Lastly a PCA model was used on the scaled data, and the same analysis was done on the transformed data. Both methods' elbow curves demonstrated that the optimal value for clustering is k = 4. 

## Results 
Original Data
* Using k = 4 clusters
<img width="748" alt="Screen Shot 2023-08-02 at 9 33 30 PM" src="https://github.com/lorelac2/CryptoClustering/assets/115598249/4af45914-b094-4b4f-a83b-33e61fddf57e">
<img width="708" alt="Screen Shot 2023-08-02 at 9 34 17 PM" src="https://github.com/lorelac2/CryptoClustering/assets/115598249/e5471109-4ffb-4d18-a486-ea32f3a91932">

&nbsp;


PCA Data
* Using k = 4 clusters
<img width="722" alt="Screen Shot 2023-08-02 at 9 34 46 PM" src="https://github.com/lorelac2/CryptoClustering/assets/115598249/ce2ba634-0dee-4649-a25d-a96baecf721b">
<img width="706" alt="Screen Shot 2023-08-02 at 9 35 02 PM" src="https://github.com/lorelac2/CryptoClustering/assets/115598249/72a4ae69-69c0-45b5-8fbd-ebbc147e1025">




## Technologies Used
Python, Pandas, Jupyter, StandardScaler, hvplot, sklearn, PCA, Kmeans
