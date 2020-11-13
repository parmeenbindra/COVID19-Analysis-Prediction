# COVID-19 Analysis and Future Prediction

Using this repository I have been trying to analyze the spread of the novel COVID-19 virus, also known as SARS-CoV-2, across the world.
Data has been taken from Johns Hopkins University (https://github.com/CSSEGISandData/COVID-19), which is updated daily.
I started working on this notebook on Nov. 5, 2020, therefore I have data until this date.

1. I have written various helper functions using Python libraries (NumPy, Pandas) to extract important data parameters. I then used these parameters to analyze the spread of COVID cases in different countries and their provinces. 

2. I have used different visualization techniques of line charts, bar plots and pie charts for easier understanding. I also wrote functions to automate visualization tasks for different countries and provinces. In my primary analyses, I have included countries only with the highest cases (USA, India, Brazil, (and China, to understand the start of the pandemic)).

3. I have used various data modelling techniques to predict the increase in cases over the next few days. I have also included a comparison of SVM, Linear Regressions, and Bayesian Ridge Regressions for future prediction. Out of the 3, SVM seemed to have the most accurate predictions on Nov. 11 - Nov. 21 predictions. 
