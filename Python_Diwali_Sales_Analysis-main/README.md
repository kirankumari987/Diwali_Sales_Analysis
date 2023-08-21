# Python_Diwali_Sales_Analysis

**OBJECTIVES OF THE PROJECT ARE -**
To analyse Diwali sales on the basis of diffetent products, gender, state, age, occupation and zone area of the customers.
Improving customer experience by analyze sales data.
Increase revenue.

1) Firstly I have to import libraries such as pandas, NumPy, matplotlib and seaborn in jupyter notebook

Loading .csv file using pandas
load the csv file containing all the raw data using pandas function pd.read_csc()

**Data Cleaning**

After removal of useless columns, we have the raw data file but it is uncleaned and contains null values. To check that null values we have to run code using pandas as pd.isnull(df).sum() When any row has null values then to eliminate such null values we call command of pd.dropna(inplace=True)

If we want to find min, max, avg, total, standard deviation, 25%, 50%, 75% etc we use df.describe()

Now after cleaning data its time to analyze data So now we are going for

**Exploratory Data Analysis (EDA)**

**Gender**
Now by using seaborn we will analyse data and plot graph of [count vs gender] We get to know that female count is more than that of male.

Then plot graph of [amount vs gender] we get to know that females spent more amount than male.

**Age**
Plotted graph of [count vs age group] and applied legend of gender to seperate bars on the basis of gender we analyse that females of age group 26–35 did most buying.

Plotted graph of [amount vs age group] we analyse that most of the buyers are of age group 26–35 years female.

**State**
Now we are going to anlyse [orders vs state] using seaborn From above graph we can see that most of the orders are from Uttar Pradesh, Maharashtra and Karnataka respectively.

We plotted graph of [amount vs state] From above graphs we can see that most of the total amount are from Uttar Pradesh, Maharashtra and Karnataka respectively.

**Marital Status**
Firstly we analyse the number of married and unmarried customers for that, need to plot graph of [count vs marital status] After plotting graph we can see that, most of the buyers are married.

Then we plotted graph of [amount vs marital status] and applied legend of gender to seperate bars on the basis of gender. we can see that most of the buyers are married womens.

**Occupation**
So, we have to anlyse occupation wise count and amount of customers We have to plot graph of [count vs occupation] and also plot graph of [amount vs occupation] From above graphs we can see that most of the buyers are working in IT, Healthcare and Aviation sector.

**Product Category**
Need to plot graphs of [count vs product category] and [amount vs product category] From above graphs we can see that most of the sold products are from Food, Clothing and Electronics category.

**CONCLUSION OF THE PROJECT**
Married women of age group 26–35 years from Uttar Pradesh, Maharastra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics category




