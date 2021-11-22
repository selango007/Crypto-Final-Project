# Crypto-Final-Project

**Selected topic**

The selected topic for the final project is Crypto Currency Price prediction for next 30 days.

**Reason they selected the topic**

I would like to predict the Bitcoin price for the next 30 days based on the historical data available. Tyat way the investors would know when is the best time to invest in Bitcoin .

**Description of the source of data**

The data source files are downloaded from Kaggle with the following details in each CSV files.

Name
Symbol
Date
High
Low
Open
Close
Volume
Marketcap

There are 23 CSV files 1 for each coins listed below.
Aave
BinanceCoin
Bitcoin
Cardano
Chainlink
Cosmos
Cryptocomcoin
Dogecoin
EOS
Ethereum
Iota
Litecoin
Monero
NEM
Polkadot
Solana
Stellar
Tether
Tron
Uniswap
USDcoin
Wrappedbitcoin
XRP



**Questions they hope to answer with the data**
Is the closing price and marketcap healthy for Bitcoin?
What will be the price of Bitcoin in the next 30 days?
Will there is a dip in price which will enable the investors to accumulate more Bitcoins?

**Results**
1. **Closing price of Bitcoin** reached more than $60000. However there is a huge drop in pricefrm it's All Time High to just above $30000 within few days interval.

<img width="839" alt="Screen Shot 2021-11-18 at 8 49 59 PM" src="https://user-images.githubusercontent.com/85666764/142566843-8f3a04fc-528f-4ed1-9621-7d2ce8cdf410.png">

2. **Market Cap of Bitcoin** is healthy based on the graph below which indicates that the Bitcoin price will be bullish.

<img width="812" alt="Screen Shot 2021-11-18 at 8 54 43 PM" src="https://user-images.githubusercontent.com/85666764/142567249-b30bf6f7-54ab-4670-8104-6857eefb9026.png">

3. **Bitcoin Price Prediction** is very volatile for the next 30 days. Within the next 10 days the price is expected to reach around $40000 and then drop back to average of $35000. Bitcoin will be a good buy 2 weeks from now. Bitcoin price prediction is performed using Linear Regression model.

<img width="901" alt="Screen Shot 2021-11-18 at 8 59 19 PM" src="https://user-images.githubusercontent.com/85666764/142567543-9f9a7fc0-206d-4465-b463-b2d5115bc0d5.png">

## Overview Of the Project
   The Overview of the project is as mentioned above this project has a dataset of 23 csv files data of cryptocurrencies. It has 23 crypto coins data one file for each coin.
### Purpose
    The Purpose of this project is to analyze the historical data and generate some graphical visualization in Tableau to know the growth of the crypto coins for business and individuals.
## Results
   The Results of this project is in the form of graphical representations as we can see them in the below screenshots from both jupyter notebook and Tableau.
   1. Concatenated all 23 files to single csv file.
   ![image](https://user-images.githubusercontent.com/86328230/142767575-4f139544-0521-45c6-8c76-bfe79f254e9c.png)

   2.Creating new columns in jupyter notebook by doing some calculations and added those new columns to csv file.
   ![image](https://user-images.githubusercontent.com/86328230/142767613-24a22f1d-4a36-42b3-825a-104680349bc8.png)
   
   3.Uploaded the above  concatenated CSV file to database as you can see the below screenshot.
   ![image](https://user-images.githubusercontent.com/86328230/142767758-1f4500d6-7664-4130-af7b-86eb838261de.png)
   
   4.Also uploaded the Prediction data of Bitcoin for next 30 days csv file to database and also some sql queries from the below screen shot 
   ![image](https://user-images.githubusercontent.com/86328230/142767929-0b6a0c1e-0612-4c77-bc26-cdae2a5c63f2.png)
   5.Created some tableau dashboard reports with the both tables.here are some.
   ![image](https://user-images.githubusercontent.com/86328230/142768023-c87b47a0-f4d3-455d-b44c-2cf677516e9e.png)
   In the above report I am showing the number of crypto coins and the sum of the volume and market cap of each coin in that particular year.
   6.In the below screenshot I am showing the summary of the cryptos in bar graph like sum of closing price on each year,sum of volume on each year and percentage      of volume on each year with the drop down of all 23 crypto coins and the below graph is the line graph of selected crypto coin per average closing price on        each day
   ![image](https://user-images.githubusercontent.com/86328230/142768311-98bedca0-288f-45de-b31b-6df23d5c1a64.png)
   7. In the below screenshot for 1st graph, I am showing the crypto coin price with volatility for selected days and price range from the available drop down          menu. Here where as volatility is calculated as Low,medium,high in pandasas you can see from the above jupyter notebook screenshots.
     In the below second graph I am showing the  bar graph of each selected coin with the details of average closing price and sum of volume  with color volatility 
     different colors for all low,medium and high.
   ![image](https://user-images.githubusercontent.com/86328230/142768401-c4a34cb9-cb8f-47bd-905d-8a2a8491f54d.png)
   
   8. In the below graph I am showing the prediction of Bitcoin price for next 30 days by using machine learning programing techniques. 
   
   ![image](https://user-images.githubusercontent.com/86328230/142768845-87e97423-467d-41c6-95e1-4583db1e165e.png)

#  Summary of this Project:
     The summary of this project is to analyze the historical data and show the analysis in the graphical, table representation in Tableau and also predict the future growth or price of the crypto coins.
     And also By using all the above analysis results we can decide when is the good time to invest in which crypto coin and also which crypto coin  growth is more.Also, please find the below link for my complete view of  Tableau project UI dashboard.

 [Link to Tableau Dashboard]: https://public.tableau.com/app/profile/sowmya.vemulapalli4674/viz/Final_Project_Cryptocurrencies/Cryptocurrencies_Analysis?publish=yes






