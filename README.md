
# Dependencies
- Language: _i.e Python 3.8.3 and/or R 4.05_
- Packages / Libraries: _i.e pandas, pyspark, sklearn, statsmodels, folium, etc... OR add a `requirements.txt`_

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- External dataset 1: https://www.statista.com/statistics/1109711/coronavirus-cases-by-date-new-york-city/    (The .csv file was provided in the raw_data because the website exports in .xlsx with multiple worksheets)

# Run in Order
1. download_files.ipynb
2. Full Dataset Analysis.ipynb
3. Preprocessing and Analysis.ipynb
4. Attribute Visualisation.ipynb
5. Statistical Modelling.ipynb

# Directory
_Change this to fit your needs when you have started the project._
- `raw_data`: Contains all the raw data files. You may add this folder to `.gitignore` if your files are too large, but you **must** provide code to automatically download or links so that we may manually download them. 
- `preprocessed_data`: Contains all the preprocessed data files. You may add this folder to `.gitignore` if your files are too large, but your script should automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
    - Notebook 1 for "Extracting Data" and "Installing Packages".
    - Notebook 2 for "Preprocessing" and/or "Exploratory Data Analysis".
    - Notebook 3 for "Analysis and Visualisation".
    - Notebook 4 for "Statistical Modelling".
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.


