# 2025_PROJECTS
The goal of this repository is to present a sample of my skills in areas of data analysis and modeling. The repository includes 3 projects with brief descriptions presented below. Detailed descriptions can be found inside their notebooks. The scope of work and level of details were settled based on amount of available time.
<ol>
  <li><b>Wind speed distribution fitting</b></li>
The goal was to try to fit selected distributions to wind speed data acquired from a NASA website. The project includes among others: data preparation, statistical data analysis, distributions fitting using method of moments and maximum likelihood estimation, distribution fitting evaluation, optimisation using derivatives (local maximum).
  <li><b>Wind turbine modeling</b></li>
In this project a wind turbine was modeled based on the same meteorological data as used in the above project. The turbine modeling included 3 scenarios: turbine with perfect orientation towards wind direction, fixed position, and fully rotatable with fixed yaw misalignment error. The project includes among others: data preparation, wind turbine modeling, component vector calculation, energy production optimisation, models comparison.
  <li><b>Monte Carlo simulations on PLN/EUR exchange rate - IN PROGRESS</b></li>
The goal of this work is to test several Monte Carlo methods on PLN/EUR exchange rate log returns in order to analyse exchange rate volatility over a 1-year horizon. The project includes among others: downloading data via an API, data preprocessing, exploratory data analysis, identyfing relevant data range, bootstrap, geometric Brownian motion, statistical distributions, hypothesis testing, distributions fitting, distribution fitting evaluation.
</ol>

Apart from the projects included in the depository, I planned more of them. However, these project are on hold due to lack of time. Such projects are:
<ul>
  <li><b>My dog's daily food consumption</b></li>
I note in an Excel file all meals my dog eats which is: date, meal number in the day, meal's amount in grams, and my dog's weight. I do this to be aware of his food preferences, identify how much he eats each day and identify potential illness. I realised I could use this dataset to model his daily consumption. I prepared ARIMA model but errors are quite high, so I decided it needs to be polished. My idea is to use neural networks (NN) to model these errors and also to model the entire consumption. Such hybrid and pure NN models results could be evaluated and compared to determine whether any on them can be reliable and which performs better. Moreover, I think about applying GARCH as ARIMA's error model.
  <li><b>Sleeping stability</b></li>
I note in an Excel file my sleeping stability each day which is a dicitonary {-1: I woke up and did not go back to sleep, 0: I woke up and went back to sleep, 1: I did not wake up} whose key/value pairs are assigned to each night. I analysed my sleeping quality by comparing different aggegations (months, year-months, day of the week etc.) between each other, and performing bootstrap simulations together with evaluating generated scenarios. The next step I plan is to make time series models to try to predict my future nights.
</ul>
