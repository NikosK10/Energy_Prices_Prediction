# Energy_Prices_Predictions

In this project, we aim to predict electrical energy prices using Machine Learning and Deep Learning methods. Specifically, we are given a dummy dataset containing features such as date, temperature, electricity demand, wind speed, solar radiation, weekday, and electricity price, among others. Our goal is to predict the price at a specific hour of the day.

After performing the appropriate preprocessing, we begin by using regressors such as Random Forest Regressor and XGBoost Regressor. However, we observe that these classic machine learning algorithms yield a significant error in our predictions.

Subsequently, we test two Deep Learning models, MLP and LSTM. Using LSTM, we achieve an error that is half that of the previous algorithms. However, the error remains high, indicating that the problem requires further analysis. We highlight that the dummy dataset may contain issues that introduce noise into our data, which in turn affects the performance of our models.

This project was created by me as a student in my effort to explore the world of Machine Learning and Deep Learning, even though I have not yet completed the Deep Learning and Neural Networks course at my school. As a result, mistakes may have been made, and this is merely a beginner's approach to the challenging and complex time series problem of energy price prediction.
