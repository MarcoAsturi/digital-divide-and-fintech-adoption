# Digital Divide and Fintech Adoption in Italy

This repository contains the analysis and predictive modeling of Fintech adoption determinants and their relationship with the digital divide in Italy, based on the **IACOFI 2023** survey (*Surveys on Financial Literacy and Digital Financial Skills in Italy: Adults*) published by Banca d'Italia.

## Project Structure

The project is organized into the following Jupyter Notebooks:

1. **desc_analysis.ipynb**: Detailed descriptive and demographic profiling of financial literacy and digital skills across the Italian population.
2. **correlation.ipynb**: Exploratory correlation analysis between socio-demographic features, digital engagement and financial knowledge.
3. **clustering.ipynb**: Advanced unsupervised segmentation (K-Means, Agglomerative Hierarchical Clustering and GMM) classifying the population into four distinct archetypes:
   - *Digital Pragmatists*
   - *Conscious Theorists*
   - *Analogue Traditionalists*
   - *Vulnerable Excluded*
4. **predictive_modeling.ipynb**: Machine learning classification pipeline (Logistic Regression, Random Forest and Gradient Boosting) to predict high Fintech adoption.


## Dataset Access

The raw survey microdata used in this project can be requested for research purposes directly from Banca d'Italia's website:
* Official survey page & publications: [Financial literacy of Italian adults](https://www.bancaditalia.it/statistiche/tematiche/indagini-famiglie-imprese/alfabetizzazione/index.html?com.dotmarketing.htmlpage.language=1)

The dataset should be placed locally at `Database_STATA_EN/Database_ENG.dta`.

## Getting Started

To run the notebooks, install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```
