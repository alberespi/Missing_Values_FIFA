# **Sudy and Treatment of Missing Values in the Overall Performance on FIFA Players Data**

This is the code I developed to write my bachelor's thesis. Missing values are a common problem in data analysis affecting tyhe quality and reliability of the results. Incomplete data can lead to biased or incoherent results, so its crucial to develop apporpiate techniques to deal with missing data.
The data is limited to the FIFA 23 players. Each player has a series of attributes that describe the performance on the field. All these attributes are grouped into the main features of the players: *pace*, *shooting*, *passing*, *dribbling*, *defense* and *physicality*. Depending on the value of these attributes, it is given an *overall* that describes the overall performance of the player. The higher the value of the overall, the better the player.

---

## The phases of the project are:
1. Previsualizde and clean the data to generate the first complete dataset
2. Introducing missing values in the complete and cleaned data manually using algorithms to generate a set of incomplete dataset (With the three types of missing values, with different proportions of incompleteness...).
3. Apply the different types of imputation techniques to the incomplete dataset to generate new complete datasets.
4. Apply machine learning models to predict the *overall* performance of the players in the first complete dataset and the imputed datasets.
5. Compare the results obtained and study the performance of the imputation techniques.

---

This is an example of all the results obtained using the R2 score:

![image](https://github.com/alberespi/Missing_Values_FIFA/assets/48257763/b6b7c505-3377-4df2-a3b7-785971b0e4c2)
