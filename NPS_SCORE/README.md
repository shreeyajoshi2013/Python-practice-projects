# Calculation of Net Promoter Score by creating clean functions


### Highlights

* use of Context Manager with open()
* aggregation
* .concat()
* .apply()



### What I learnt newly?

* Standards for writing docstrings in Python, Google-style (chosen style in this notebook)

### What is being done?

1) Function to convert CSV file into a dataframe. Add a column for the source category name. <br>
2) Function that verifies that the files inputted are valid (i.e., in the required format).<br>
3) Function to concatenate the dataframes into one.<br>
4) Function to categorize the NPS rating into appropriate group.<br>
5) Function that adds a column for the NPS group and populate it depending on the rating.<br>
6) Function to calculate the NPS across all sources.<br>
 

### Conclusion:

From amongst the source categories – email, mobile, and web, the mobile responses have an NPS score of about -15, which is noticeably lower than the other two sources. <br>
Hence it is a data-driven inference that people are rating lower on the mobile than other sources. So, this is some evidence that the mobile app UI experience needs an improvement. 

### References:

 https://www.datacamp.com <br>