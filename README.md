# LendingClub_DataAnalysis


Steps to run the docker Image:

docker pull melavoyrajap/ads_assignment2


docker run -it -e "accesskey=<enter your accesskey>" -e "secretkey=<enter your secretkey>" -e "bucket=<enter your bucket>" -e "loanDataFile=<enter filename>" 
-e "rejectLoanDataFile=<enter filename>" melavoyrajap/ads_assignment2:latest
 


Scripts/Notebooks:

Clustering
R script to perform clustering to segment data into clusters.

Part1
Data Wrangling and Exploratory Data Analysis
Used Luigi to pipeline whole process
Dockerized and scheduled the pipeline using cron job.

Prediction&ClassificationModels
Predictive models(Random Forest, Neural Network, Linear regression, Knn) Scripts to predict interest rate using data from clustering methodologies
Classification Models Scripts that will generate a flag whether to give loan or not.

complete_webapp: Front end application code

 
