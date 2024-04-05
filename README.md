# **Bank_user_dataset_EDA**
### **Introduction**

This notebook focuses on researching statistical information regarding the customer's banking profile. In this book, we will explore and use EDA techniques to gain insight.

### **Defining the problem statement**
The dataset contains various credit related variable like credit age, types of loan, credit utilization and so on along with their credit score categorised into Good, Standard and bad. We want to analyze which variables influences the credit score and how.

![](images/images.jpeg)

### **Methodology**
For this particular notebook, we will first resolve the data's inconsistency caused by incorrectt data types and entries using first regex to find the correct value and then coverting them to suitable datatype. Continuing the cleanup process, we resolve missing values by grouping the data on customer id and imputing them with average or mode based on the column. Next we drop all the unneccseray and inconsistent columns. We then created dummy data to handle categorical data by crating our own custom method to retain multiple count of same loan. We later handled credit history age by converting ages to months. Now, concluding the data to gain insights drawn with visualizations.

### **Insights**
* There is a direct relationship between age and credit score, more the age the better is the credit score of the individual.
* The worst credit score is for individuals with least credit history age.
* The good credit score requires atleast 14 years of credit history.
* Occupation has no effect on late payments neither on credit score.
* Young individuals are more likely to not pay the dues in time which affects their credit score.
* Owning multiple credit cards, in general more than 4 is discouraged for good credit score.
* Credit utilization also impact credit score to some extent. Higher credit utilization improve the credit score.
* Paying the dues on time leads to better credit score.
* Paying the dues one month after significantly reduces the credit score.
