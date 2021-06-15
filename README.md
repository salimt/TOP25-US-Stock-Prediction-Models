
# TOP25-US-Stock-Prediction-Models

<center><img src="https://i.imgur.com/6OzPtKu.png" alt="drawing" width=500/></center>

Accurately predicting the future behaviours of stock markets would be extremely valuable for traders. However, the task is challenging, as financial markets can be dynamic, non-stationary, and noisy. Above all, the efficient market hypothesis states that current stock prices reflect all available knowledge, indicating the futility of using past historical data and financial new to forecast the future prices of stocks.

In this project, we exhaustively investigates the performance of various machine learning algorithms, including standard, ensemble, and neural networks, for predicting the daily movement of stock markets conditioned on historical data of diverse market-specific, general economic and other relevant financial variables. 

The objective of the project is to perform data visulalization techniques to understand the insight of the data. Machine learning often required to getting the understanding of the data and its insights. This project aims apply various [Python](https://www.python.org/) tools to get a visual understanding of the data and clean it to make it ready to apply machine learning opertation on it.

## Installation
This is an exe file. Package requirements are included in requirement.txt. This project uses Python 3.9.
Run the following command in terminal to install the required packages. 
`pip3 install -r requirements.txt` 

## Usage
The app includes all the markdowns which explain the process. 

## Data-set examination
#### The data-set is in CSV format that includes:
* The train data-set has 70 percent of the last 12 years and 1 target variable.
* The test data-set has 30 percent.
* The target variable is the CLOSE price.

## Summary
<img src="https://i.imgur.com/AKCaCA3.png" alt="drawing" width="500"/>

<img src="https://i.imgur.com/wxZXae2.png" alt="drawing" width="500"/>

<img src="https://i.imgur.com/GYP1Aej.png" alt="drawing" width="500"/>

After the result comparison, I still need to put more effort to improve the model. The result reflects that some of the valuable data might not yet to be discovered from the dataset. Probably need to review all the missing data, outliers, also, spend more time on data analysis and multicollinearity issue.

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :)

## Authors
This repo is maintained by salimt.
