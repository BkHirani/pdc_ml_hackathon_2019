## Petition Victory Prediction

Change.org is having huge number of petitions data which contains many columns. From this data we have to predict weather the current petition will be successful or not. 

### Solution Highlights

There were two problems to solve:
1. To predict wheather the petition will be successful or not.
2. To predict the category of Petition from data.

So, we used XGBoost Algorithm here for generating efficient supervised classification algorithm. We tried almost all classfication algorithms, but XGBoost was providing best accuracy among them all, so we used that algorithm in final solution.

Here, there are 4 files submitted by us.
1. PDC_Hackathon.ipynb - This file contains algorithm for predicting wheater petition will be Victory or not.
2. Categorical Classification_Modified.ipynb - This file contains algorithm for predicting  category of petition from its description.
3. Visualization.ipynb - This file contains extra graphical visualization of data, but its not that important. Its just for extra refences.
4. final_out.csv - This file contains final submission of validation data.

### Data

Data was shared by organizers, which contains 68 columns and around data of 13K petitions. The challenge here was we need to identify the truly affected columns from data and It was the web scrapped data. So, we have to clean that, too.

### Dependencies

* python 3
* scikit-learn
* pandas
* XGBoost
* numpy

We used Anaconda for this work.

### Default Run

We have submitted jupyter notebook code itself. So, please consider it run all along. Out model is giving great accuracy of above *90%* in both problems, we have tried it with real time data from website and gave almost correct output in most cases.



