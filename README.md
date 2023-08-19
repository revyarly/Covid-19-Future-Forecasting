# COVID-19 Future Forecasting

The aim of this study is to forecast the future spread of COVID-19, focusing on the number of new positive cases, deaths, and recoveries. The purpose of this study is to help prepare for and mitigate the potential threat to humanity posed by the virus.

## Dataset
The data used in this study is obtained from the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) COVID-19 dataset. This dataset contains daily reports of the number of confirmed cases, deaths, and recoveries for countries and regions around the world.

https://github.com/CSSEGISandData

## Models & Evaluation Metrics

Three types of predictions are made by each of the models, such as the number of newly infected cases, the number of deaths, and the number of recoveries in the next 10 days. Three different models are used for forecasting:

**Models:**
- Linear Regression
- Polynomial Regression
- Support Vector Machine 

To evaluate the performance of these models, three evaluation metrics are used:

**Evaluation Metrics:**
- R-squared
- Mean Square Error 
- Root Mean Square Error
## Tech Stack

**Programming Languages:** Python

**Packages and Modules:** Numpy, Pandas, Matplotlib, Math, Scikit-learn, Datetime, operator.

## Architecture 

![architecture](https://github.com/revyarly/Covid-19-Future-Forecasting/blob/main/architecture.png)

## Documentation

Here is the link to the [documentation](https://github.com/revyarly/Covid-19-Future-Forecasting/blob/main/documentation.pdf)

## Repository Structure

 - `src_code`: contains the main code for the project
 - `documentation` : contains the indepth explanation of the processes in the code 
 - `architecture`: contains the project architecture
## Usage

To reproduce the predictions, follow these steps:

1. Clone the repository
2. Install the required packages (listed in **packages and modules**)
3. Run the **src_code** to preprocess the data and train the models and make the predictions

**Note:** refer to **architecture** to understand the procedure  

## Conclusion

The study demonstrates the potential of machine learning models for predicting COVID-19 trends. The results suggest that LR is a more effective method for predicting COVID-19 trends than SVM. The study findings can be useful for policymakers, healthcare professionals, and the general public in preparing for and mitigating the impact of COVID-19. However, it is important to note that these predictions are based on past data and may not accurately predict future trends. Continued monitoring and analysis of COVID-19 data are necessary to make informed decisions about managing the spread of the virus.
