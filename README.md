## 1. About Project:
Analysis and Visualization of data on startup companies and investments in a particular market and plotting Year on Year Founding and Funding trends.
Data Source : Crunchbase data on startup companies and investments in AI in Fintech Market till Dec 2018


## 2. Raw Data and Output Preview

### 2.a. Raw Data

#### startup market data csv files (Data Source: Crunchbase)

* 'companyData.csv'
![alt text](file:///c:/Users/pawankumargali/Desktop/rawCompData.png)

* 'investmentData.csv'
![alt text](file:///c:/Users/pawankumargali/Desktop/rawInvData.png)

#### currency exchnage rates csv file (Data Source: European Central Bank)

* 'historicalCurrencyExchangeRates.csv'
![alt text](file:///c:/Users/pawankumargali/Desktop/currencyConverterData.png)

### 2.b. Output

Output Plots can be previewed in the output/plots/ folder. Previewing two of them here

* YoY - Total Funding Amount and Funding Rounds
![alt text](https://raw.githubusercontent.com/pawankumargali/startupDataAnalysis/master/output/plots/2_YoY-Total_Funding_Rounds.png)

* YoY - Funding Amount by Stage
![alt text](https://raw.githubusercontent.com/pawankumargali/startupDataAnalysis/master/output/plots/5b_YoY-Funding_Amount_by_Stage.png)
    


## 3. Folder Structure:

![alt text](file:///c:/Users/pawankumargali/Desktop/fs1.png)

### 3.a. Folders:

#### 3.a.i. raw_data/  folder:
- includes raw csv files which can't be fed as input for our analysis and have to be further formatted
- Contains startup companies and investments csv files (source: crunchbase)
- Contains  historical currency exchange rates csv files in currency_exchange_rates/ sub-folder (source: from European Central Bank)

![alt text](file:///c:/Users/pawankumargali/Desktop/raw_dat.png)


#### 3.a.ii.input_data/ folder:
- Includes formatted csv files to be fed as input for our analysis
- Contains startup companies and investments formatted csv files
- Also contains formatted currency exchange rates csv files that will be used as reference for
converting all Funding Amounts to USD during analysis

![alt text](file:///c:/Users/pawankumargali/Desktop/inp_dat.png)


#### 3.a.iii output/ folder:
- used to store results extracted from data analysis and visualization
- extracted data is stored in output excel file and 
- visulaizations are stored as png files in plots/ folder

![alt text](file:///c:/Users/pawankumargali/Desktop/out_dat.png)


### 3.b. Files:

- ipynb files numbered 1-7 perform analysis on input data from input/ folder and 
save extracted data and visualization(s) to output/ folder. 

- ipynb files 'companyDataMunging', 'investmentDataMunging' and 'currencyConverterMunging'
convert raw data csv files from raw_data/ folder, to formatted csv files and save them to input_data/ folder

* Note: All ipynb files are self-explanatory, i.e., how the analysis or formatting is carried out is detailed in the file itself.

    