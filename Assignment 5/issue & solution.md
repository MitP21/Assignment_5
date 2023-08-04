I began by determining whether the dataset was clean. However, it was tidy. 
I have the identical column with the name "age" in both datasets. 
The dataset merge then encounters an issue. Although I tried to merge them with the age column, 
I kept getting syntax errors. Then, with some assistance from Google, we discovered that we needed to utilize the "on=" method to combine two datasets that shared a single column.
I entered "on = 'age'" at the end to combine two datasets.
