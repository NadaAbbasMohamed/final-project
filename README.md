# final-project
The main idea of the project is to scrap for the latest applications on the app store analyse its features and properties as app rating, no of installs ... etc to gain insight about the the best combination of features to have a popular app with large number of installs. then create a predictive model to predict if your app is more fit to be successful or not and through clustering determine which category is your app in.

## Steps of the project:
- web scrapping : to collect data
- database design to store the collected data
- data cleaning, visualization, and feature engineering (preprocessing)
- data investigating through visualization and creating insights about the popular/ successful apps
- dimensionality reduction
- ML. regression task for predicting number of installs based on app features
- Unsupervised learning clustering to know the main clusters of applications based on its features
- deployement as a web application

## files in the project are as follows:
- Scrapping part: 1- Scrapping part1.ipynb --> for scrapping home page, 2-Scrapping part2.ipynb --> for scrapping all apps under the see more button
- Data base deployment: 1- databaseImplementation.ipynb --> python script to create and fill the data base, 2- APPS_table.db --> all apps added to a single table, 3-apps_RDBMS.db --> contain the implementation for the scheme of the RDBMS for the apps and their features as relational tables 
- all the data analysis operations and the ML models: EDAandML.ipynb
