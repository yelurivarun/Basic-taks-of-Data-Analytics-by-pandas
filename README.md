# Basic-taks-of-Data-Analytics-by-pandas
Here are some basic tasks in data analytics by pandas and i have mentiond all the csv files , solution file

      ------------------------Explanation of tasks----------------------
https://drive.google.com/file/d/1J8yXJBpUltyuuCrgDM_qH3iqz_4skOmY/view?usp=drive_link 
df= pd.read_csv(r”C:\Users\Doc\sample.csv”)  # importing file from a locationdf = pd.read_excel(“sample.csv”)
df.isnull()     # returns a dataframe with Boolean values for the null values
df.isnull().sum()     # returns no. of nulls for each col
df.head()       # displays top 5 rows
df.head(10)       # displays top 10 rowsdf.tail(6)                             # displays last 6 row
pd.mereg(df1, df2,how='outer)        # returns all the data
df['colname']  #accsessing single col
