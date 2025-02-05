# DataProjects

This repository contains my old projects during my university years and internship, and other personal projects. Some, if not all of them may not be perfect, but they are pretty interesting and valuable to my journey as a data analyst/scientist. Note that some of the dataset (usually from certain companies) will not be published.

Complete List of Projects Here (In chronological order):
1. Forecasting of New Zealand Temperature: A group project for time series course in the 4th Semester. We managed to get 94% accuracy on SMA(0,0,1)(0,1,1)12 and SARIMA(1,0,1)(2,1,1)12 model when forecasting New Zealand's average monthly temperature.
   
2. Simultaneous Equation Model Analysis of USA National Income: Also a group project for econometrics course in the 4th Semester. We did SEM analysis on USA National Income using G Menges' econometrics submodel for the West German economy in 1975. The best model is the log-transformed SEM model since it has the highest R-squared and is able to fullfil all of the classic assumption for the regression.

3. Smartphone Brand Analysis: An individual project for my Data Science Class in 6th Semester of University. Basically I analyzed customer's smartphone data and try to come up with an insight for a company, in this case Samsung. 

4. Fraud Detection: A group project for my Data Science Class. Utilizing H2O, we managed to get 0.48 on F1-Score using Gradient Boosting to predict fraud.

5. (On Hold) Memecoin (PEPE) Price Predictor: I tried to make an alert to predict PEPE's price. Basically the script would gather data through dexscreener's API for a period of time, then predict the price using an LSTM Model. I do not have a proper setup to run data gathering 24/7, which makes it fairly difficult to train the LSTM model. Even then, gathering data for a short period of time and immediately predicting the price might possess a huge challenge since Cryptocurrency, especially Memecoins are prone to market manipulation, which makes technical analysis even harder. Using Twitter API to gather sentiment might help, but I need to commit a huge amount of money for it just to get higher access of Twitter API. For those reasons, I will postpone this project indefinitely. It was a good lesson.

6. (Ongoing) Twitter Bot for Shitposting: I am creating a twitter bot to make a post based on current twitter top trends. The bot will post in random intervals and to ensure more humanlike nature. It uses AI (you know why).
