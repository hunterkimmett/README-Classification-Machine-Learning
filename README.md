# README-Classification-Machine-Learning

## Project Overview

GitHub serves as a large repository containing the programs of millions of users and their programs. README files are often included in GitHub repositories and are critical to a user’s understanding of how a program functions. One of their most important tasks is to inform the user on how to run their program.

In this project our group tried to replicate and improve the results of the paper ​'Categorizing the Content of GitHub README Files' for categorizing README files that contain the methods on how to run their program. We will try to improve the results of this paper by expanding on their dataset and tuning their best machine learning algorithm (Linear Support Vector Machine Classifier) and a new machine learning algorithm (Gradient Boosted Tree Classifier) .

The Gradient Boosted Tree Classifier performed adequately but could not match the results of the paper even after adding our new dataset and tuning its hyperparameters. The Linear Support Vector Machine Classifier however was able to outperform the paper’s classifier on both the original dataset and our new dataset. Through this paper it is demonstrated that tuning and the addition of more data can improve the results of a machine learning algorithm’s predictions of if a README file explains how a program works.

## Contents

input/: README markdown files to be analyzed

output/: .csv files containing the information from the README files, output by helper scripts

script/: helper scripts to extract information from README files

RandomRepo.ipynb: Jupyter Notebook used to randomly find a Github repository to be used for the project

README Classification Report.pdf: Report submitted as a part of our assignment

README-Classifier.ipynb: Databricks Notebook with the classifier as a Jupyter Notebook. Available as a Databricks Notebook at this link:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4985770712986055/1653466948958185/3712725817297160/latest.html