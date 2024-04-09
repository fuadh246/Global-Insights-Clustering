# Global-Insights-Clustering
Global Insights: Country Clustering Analysis Using Unsupervised Machine Learning

## Overview
With so many disasters happening all around the world, it’s important for us to know where aid should go first. There are countries that are self-sustained and there are other countries that rely on funds to be sent. So how can we determine what countries need aid first? HELP International makes a difference in the lives of everyday people across underdeveloped regions. It’s important for us to categorize countries based on socio-economic and health factors to assess their overall development. Through this final project, I hope to sort countries into 4 categories, Upper-Middle Developed, Lower-Middle Developed, Highly Developed, and Least developed countries based  on features like Child mortality rate, Import / Exports of goods, Total health spending, Net income per person, life expectancy, and the GDP per capita. Overall aiming to help countries that need the most aid.

![image](https://github.com/fuadh246/Global-Insights-Clustering/assets/93026516/22d90da7-98f1-4f55-a3d4-b045e0694b18)

![Choropleth Map](/Img/choropleth_map_of_all_countries.png)

## Features
- **Data Exploration**: The notebook provides a comprehensive exploration of the dataset, including summary statistics, visualization of distributions, and identification of potential outliers.
- **Preprocessing**: Data preprocessing steps are included to clean and prepare the dataset for clustering analysis. This may involve handling missing values, feature scaling, and encoding categorical variables.
- **Clustering Algorithms**: Several clustering algorithms are implemented and evaluated in the notebook. Common algorithms such as K-means, DBSCAN, and hierarchical clustering may be utilized to cluster the data points.
- **Evaluation Metrics**: Performance metrics for evaluating clustering results are discussed and computed. These metrics help assess the quality of clustering and aid in selecting the most appropriate algorithm and parameter settings.
- **Visualization**: The notebook includes visualizations of clustering results to aid in interpretation and understanding. This may involve plotting clusters in feature space or visualizing cluster centroids.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python packages (NumPy, pandas, scikit-learn, matplotlib, seaborn)

## Usage
1. Clone the repository to your local machine:
```bash
git clone https://github.com/fuadh246/Global-Insights-Clustering.git
```
2. Navigate to the `model` directory:
```bash
cd Global-Insights-Clustering/model
```
3. Open the `Cluster.ipynb` notebook using Jupyter Notebook:
```bash
jupyter notebook Cluster.ipynb
```
4. Follow the instructions within the notebook to execute code cells and explore the clustering analysis.

## Contribution
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/)
