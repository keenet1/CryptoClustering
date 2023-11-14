# CryptoClustering

**Contributor:** Thomas Keene
---

## Background
The primary goal of this project was to use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. K-means clustering was employed as the primary analytical technique and the data was explored both in its original state as well as after reduction using Principal Component Analysis (PCA).

## Visualizations
First, a plot was generated to show the returns for several crypto currencies and for several different holding periods:

![Screenshot 2023-11-13 at 10 52 10 PM](https://github.com/keenet1/CryptoClustering/assets/137319054/b302a035-0a40-4c70-bd50-1827dbc902c5)

Elbow curves were also generated to compare the original data to the date after Principal Component Analysis
![Screenshot 2023-11-13 at 10 56 23 PM](https://github.com/keenet1/CryptoClustering/assets/137319054/b9f1f0ab-c19e-4442-b4c2-79ec9512c9ef)
![Screenshot 2023-11-13 at 10 57 06 PM](https://github.com/keenet1/CryptoClustering/assets/137319054/47c1ebd9-0335-439b-8adf-4a42c8375d8a)

The final analysis made use of cluster graphs to compare he original data to the date after Principal Component Analysis
![Screenshot 2023-11-13 at 10 59 03 PM](https://github.com/keenet1/CryptoClustering/assets/137319054/6775507b-d496-4a55-850e-f130890e25ef)
![Screenshot 2023-11-13 at 10 59 36 PM](https://github.com/keenet1/CryptoClustering/assets/137319054/3eb64a0b-a1f0-40eb-b45f-18b961f08518)

## Tools
- Scikit-learn
- StandardScaler
- Pandas
- NumPy
- PCA
- hvPlot

## Resources:
Some coding I looked at for inspiration:
- https://github.com/paocarvajal1912/Crypto_Clustering
- https://github.com/Asalvs/CryptoClustering

## Acknowledgements:
I wish to thank my teaching staff:
- Hunter Hollis
- Sam Espe
- Randy Sendek
