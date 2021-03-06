# Fruad Prevention System
![](https://www.paymentsjournal.com/wp-content/uploads/2020/03/1037-scaled.jpg)
### Why fruad detection?
Fraud is a billion-dollar business and it is increasing every year. The PwC global economic crime survey of 2018[1] found that half (49 percent) of the 7,200 companies they surveyed had experienced fraud of some kind. This is an increase from the PwC 2016 study in which slightly more than a third of organizations surveyed (36%) had experienced economic crime.
### Embarrasing story ???
Imagine standing at the check-out counter at the grocery store with a long line behind you and the cashier not-so-quietly announces that your card has been declined. Embarrassed, and certain you have the funds to cover everything needed for a party for 50 of your closest friends, you try your card again. Same result. As you step aside and allow the cashier to tend to the next customer, you receive a text message from your bank. “Press 1 if you really tried to spend $500 on cheddar cheese and beer.”
### Project objectives 
While perhaps cumbersome and often embarrassing in some customer experiences, this fraud prevention system is actually saving consumers millions of dollars per year. The crucial part of the system is to benchmark machine learning models on a challenging large-scale dataset. The data comes from real-world e-commerce transactions and contains a wide range of features from device types to product features. If successful, I will improve the efficacy of fraudulent transaction alerts for millions of people around the world, helping hundreds of thousands of businesses reduce their fraud loss and increase their revenue and better customer experiences.

### Contents

**1. Exploratory data analysis**

**2. Get rid of redundant features**
* Apply PCA on each group feature individually
* Select maximum size of unrelated features in one group
* Replace the entire group with all feature averaged

**3. Feature selection**
* Permutation importance
* Adversarial validation 
* Correlation analysis
* Time consistency

**4. Create magic features**

**5. Validation strategy**
* GroupKFold CV using month as a group

**6. Modeling**
* XGBoost with AUC 0.947
    
