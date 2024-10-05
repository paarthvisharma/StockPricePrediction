# Stock Prediction Project

This project aims to predict stock prices using machine learning models. It utilizes historical stock data and various data science techniques, such as time series analysis and machine learning algorithms, to forecast future stock prices.

## Features
- **Data Processing**: Uses `pandas` and `numpy` for efficient data manipulation.
- **Visualization**: Provides stock data visualizations using `matplotlib` and `seaborn`.
- **Machine Learning**: Implements models using `scikit-learn` for stock price prediction.
- **Interactive Notebook**: The project is contained within a Jupyter Notebook for easy interaction and experimentation.

## Files

### 1. `StockPrediction.ipynb`
The Jupyter Notebook that contains the entire workflow, including:
- Data loading and preprocessing
- Data visualization
- Model training and evaluation
- Stock prediction results

### 2. `requirements.txt`
A list of Python packages required to run the project. Use this file to install the necessary dependencies.

```bash
appnope==0.1.3
asttokens==2.4.1
comm==0.2.0
contourpy==1.2.0
cycler==0.12.1
debugpy==1.8.0
decorator==5.1.1
exceptiongroup==1.1.3
executing==2.0.1
fonttools==4.44.3
ipykernel==6.26.0
ipython==8.17.2
jedi==0.19.1
joblib==1.3.2
jupyter_client==8.6.0
jupyter_core==5.5.0
kiwisolver==1.4.5
matplotlib==3.8.2
matplotlib-inline==0.1.6
nest-asyncio==1.5.8
numpy==1.26.2
packaging==23.2
pandas==2.1.3
parso==0.8.3
pexpect==4.8.0
Pillow==10.1.0
platformdirs==4.0.0
prompt-toolkit==3.0.41
psutil==5.9.6
ptyprocess==0.7.0
pure-eval==0.2.2
Pygments==2.17.1
pyparsing==3.1.1
python-dateutil==2.8.2
pytz==2023.3.post1
pyzmq==25.1.1
scikit-learn==1.3.2
scipy==1.11.4
seaborn==0.13.0
six==1.16.0
sklearn==0.0.post11
stack-data==0.6.3
threadpoolctl==3.2.0
tornado==6.3.3
traitlets==5.13.0
tzdata==2023.3
wcwidth==0.2.10
```

## Installation

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required packages using `pip`:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook StockPrediction.ipynb
   ```

## Usage

- Open the `StockPrediction.ipynb` file in Jupyter Notebook.
- Follow the steps in the notebook to load stock data, preprocess it, and train machine learning models.
- The notebook contains various sections for data visualization, training models, and evaluating predictions.

## Dependencies

The project depends on the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
- `jupyter`

You can install all dependencies using the `requirements.txt` file.
