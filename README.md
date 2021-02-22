# Data-612 
## Assignment07
1.import needed libraries 

2. import stock data  using pd.read_csv and change date column into Timestamp using parse_dates

3. apply each part of the funcation to the data line by line and check th output.

   1st df.loc[(df.type == type_x) & df.category.isin(['category_x', 'category_xy', 'category_xyz'])
    
    2nd using 1st step out put apply .groupby([group_col, date_col]).sum()
       
       3rd using 2nd step out put apply  .unstack(date_col)['amount']
         
         4th using 2nd step out put apply .resample('M', axis=1).sum()......etc



