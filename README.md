# Sparkify Project - Udacity Data Scientist
In this project, the objective is to create a model to detect the user who will potentially leave the music streaming service platform. It is a classical churn prediction problem.

### Requirements and Considerations
- To run the project, it is needed to have an account at Databricks Community (Free tier with up to 6GB of space and unlimited time to use it).
- The project has been created in Databricks for the simplicity that the platform supports for Spark projects and the decent computing capabilities it offers at a free tier level. Some considerations should be taken for the review of the project. In the link provided in the following point, you'll be able to find the original Databricks Notebook, and in the repository we'll have the edited version in Jupyter, adding better fonts and formatting. An HTML version will also be provided.

- Databricks original notebook link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6246151171355951/1214521649023240/5956692570509628/latest.html
-  Just upload the dataset for this problem (provided by Udacity Data Scientist Nanodegree) and you'll be able to run all the cells.
- No other python packages installs are needed

### Methodology
The project has been created mainly in a jupyter notebook within Databricks. There is also a Medium blog post explaining a little bit more the steps performed during the modelling. 
https://medium.com/@manumg8/sparkify-how-to-predict-churn-rate-for-a-music-streaming-platform-976f839c24ed

### Results
The model created is based on a gradient-boost classification algorithm. It has a 55% of recall score and 85% of F1 score.  
