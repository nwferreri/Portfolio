# Portfolio: Nick Wildason-Ferreri
Welcome to my portfolio! Here I will showcase some of the Data Science/Analytics projects I've completed as I work to transition into the field.

Certificates for the courses I've completed as part of my Data Science program can be found [here](https://github.com/nwferreri/Portfolio/tree/main/Certificates).

Additional details can be found by following the link for each project.

## [Meal Kit Delivery Service Analysis using Power BI](https://github.com/nwferreri/meal-kit-delivery-powerbi)
In this project, I used Power BI to combine, transform, and analyze data about the performance of a fictional meal kit delivery service.

I created interactive dashboards with several features that rely on calculations(measures) created using DAX. These dashboards allow end users to assess and explore the company's performance.

The first dashboard is a high level overview, with tools to project revenue into the future.

![Oodles of Noodles- Summary Dashboard](https://github.com/nwferreri/meal-kit-delivery-powerbi/assets/112211174/d794f802-c9a8-41ae-a33a-92c345b4c271)

The second dashboard is a drill-through from the Revenue by Division chart in the first dashboard. It shows information specific to a selected division of the company.

![Oodles of Noodles - Division Detail Dashboard](https://github.com/nwferreri/meal-kit-delivery-powerbi/assets/112211174/669adc93-10be-42da-a2fc-7e56c992300d)

These dashboards give the company the tools it needs to assess performance and make data-driven decisions about the future.

## [Excel Personal Budget Project](https://github.com/nwferreri/excel-budget-project)
In this project, I leverage several Excel tools (fomulae, visualizations, VBA macros, pivot tables) to provide insights into personal finance.

The Summary sheet provides a high level overview, using dynamically calculated formulae and charts to provide up-to-date information.

![Screen Shot 2024-01-25 at 2 45 20 PM (2)](https://github.com/nwferreri/excel-budget-project/assets/112211174/146468b2-6327-4a84-82ae-e29f7f71d926)

The Spending Summary sheet contains a Pivot Table that allows to user to see breakdowns of their expenses by category and year/month.

![Screen Shot 2024-01-25 at 3 47 32 PM (2)](https://github.com/nwferreri/excel-budget-project/assets/112211174/192b6d55-f899-480c-970f-fbe6d695c6cc)

These worksheets allow someone to gain a greater understanding of their personal finances and identify areas for optimization and improvement.

## [Airbnb Forecasting Product](https://github.com/nwferreri/airbnb-forecasting)
In this project, I used time-series data about Airbnb demand in New York state to create a model to predict the demand for the next month.

I first performed some exploratory data analysis to learn more about the data. I discovered that there appears to be a seasonal component across the year that might affect the demand. I also discovered that demand and temperature appear to be inversely correlated, which makes sense if there is a yearly seasonal variation. The data suggests that demand is lower when the temperature is higher.

![image](https://github.com/nwferreri/airbnb-forecasting/assets/112211174/de97cdfb-e5b2-4259-9651-e4031accb40c)

Next I chose 4 models to use: Prophet, SARIMAX, LinkedIn Silverkite, and LSTM. I trained each model on the data, performed parameter tuning, and finally made predictions. Then I combined and weighted the models to create an ensemble and visualized the predictions of all 5 models.

![image](https://github.com/nwferreri/airbnb-forecasting/assets/112211174/8cc9987f-ed0a-4cb9-88ec-912fde8c4fa0)

With these trained models, Airbnb can predict future demand and prepare accordingly, confident that their decisions are driven by data.

## [Bulldozer Price Prediction](https://github.com/nwferreri/bulldozer-price-prediction)
In this project, I used time-series data on bulldozer sales and characteristics to build a machine learning model to predict the sale price of a bulldozer.

The data had a large number of missing and non-numerical values that needed to be addressed in order to run a regression machine learning model. I filled missing numerical values of each column with the column's median to avoid any effects outliers may have had on the mean. For the non-numerical columns, I converted them into pandas categories and then converted those to numbers using the category codes and incremented them by 1 to remove the missing values. Finally, the data was split into training and validation sets.

With the data prepared, I trained and tuned the initial models on a subset of the data to speed up the testing phase. Then I extracted the best parameters and trained the full model. The test data was preprocessed using the same pipeline as the training/validation sets and used to make a set of predictions.

I also extracted and visualized the feature importances of the model, with the goal of generating some valuable conclusions from the model.

![image](https://github.com/nwferreri/bulldozer-price-prediction/assets/112211174/422f1924-b350-415e-8282-6d7318697b20)

This showed that the two best indicators for predicting the price of a bulldozer are its size and the year it was made.

## [Dog Breed Image Classification using TensorFlow](https://github.com/nwferreri/dog-breed-image-classification)
Machine learning model that uses deep/transfer learning and TensorFlow to predict a dog's breed based on an image.

## [Heart Disease Classification](https://github.com/nwferreri/heart-disease-classification)
Machine learning model that predicts if a patient has heart disease.

## Other Projects
If you'd like to see more projects, a full list can be found [here](https://github.com/nwferreri/all-projects).
