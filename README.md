# Predicting Monthly Risk Premiums in the US Technology Sector
This study aims to evaluate and compare the predictive capabilities of neural networks and traditional machine learning models in forecasting monthly risk premiums of US technology stocks. By constructing a portfolio consisting of the top 10% of stocks based on predicted risk premiums, this research assesses model performance using both statistical evaluation metrics and real-world financial impact through simulated investment returns.
The portfolio's performance will be benchmarked against the Technology Select Sector SPDR Fund (XLK) to determine whether advanced predictive models can offer a competitive advantage over passive investment strategies (Leippold et al., 2022).
## Project Structure
```plaintext
dse4101/
├── data/   # Contains raw and processed datasets used in the project.              
│   ├── `final_merged_data.csv`: Cleaned dataset for analysis.
│   ├── model_results/  # Contains predictions and feature importance from various models.

├── src/               
│   ├── data_collection.ipynb  # Notebook for data collection and preprocessing
│   ├── data_merging.ipynb  # Notebook for merging preprocessed data with stock characteristics data
│   ├── eda.ipynb              # Notebook for exploratory data analysis
│   ├── results_visualisation.ipynb  # Notebook for analyzing model results

│   ├── ols.ipynb       # OLS model
│   ├── rf_model.ipynb  # Random Forest model
│   ├── lstm.ipynb      # LSTM model
│   ├── gbrt.ipynb      # GBRT model

├── .gitignore         
├── README.md          
```
## Getting Started

1. **Run Notebooks**: Open and execute the Jupyter notebooks in the `src/` directory for data processing, analysis, and modeling.