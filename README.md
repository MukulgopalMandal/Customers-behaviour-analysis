# Customer Segmentation using Clustering
This repository contains a project for **customer segmentation** using machine learning clustering algorithms. The project includes Python code in a Jupyter Notebook to preprocess customer data, apply clustering methods, and evaluate their effectiveness.

## Features
- Data preprocessing and feature scaling.
- Implementation of three clustering algorithms:
  - **K-Means**
  - **Gaussian Mixture Model (GMM)**
  - **DBSCAN**
- Visualization of clustering results.
- Comparative analysis of algorithm performance.
- Export of clustered datasets for further use.

- ## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Basic knowledge of clustering and unsupervised learning.

### Setup Instructions

1. Clone this repository to your local system:
```Bash
git clone https://github.com/yourusername/customer-segmentation.git
```
2. Navigate to the project directory:
```Bash
cd customer-segmentation
```
3. Install the required dependencies by running the following command:
```Bash
pip install -r requirements.txt
```
4. Open the Jupyter Notebook:
```Bash
jupyter notebook
```
5. Open the project.ipynb notebook and follow the step-by-step instructions.
## Usage

- Load and preprocess the dataset.

- Apply clustering algorithms (K-Means, GMM, DBSCAN).

- Evaluate results and interpret business insights.

- Visualize clusters and analyze customer groups.

## Repository Structure

```Bash
customer-segmentation/
├── customer_data.csv                  # Raw dataset
├── customer_segments_k_means.csv      # K-Means clustering output
├── customers_segments_gmm.csv         # GMM clustering output
├── customer_segments_dbscan.csv       # DBSCAN clustering output
├── project.ipynb                      # Main Jupyter Notebook
├── Data Analytics Lab - Report.docx   # Detailed project report
├── requirements.txt                   # List of dependencies
└── README.md                          # Project documentation (this file)

```
## Contributing

Contributions are welcome! Please follow these steps:

- Fork this repository.

- Create a new branch:

```Bash
git checkout -b feature-name
```

- Commit your changes:
```Bash
git commit -m "Add new feature"
```
- Push to the branch:
```Bash
git push origin feature-name
```
- Submit a pull request.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- Dataset: Kaggle - Customer Purchases Behaviour Dataset

- Open-source libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy

- References: IBM, Applied AI, GeeksforGeeks, Scikit-learn documentation
  EOF
