# Cleaning-Data-Project

For this tiny data project I took a zipped package of .txt files, ran them through R, and turned out a tall and skinny tidy data set. This data set has only the average of the mean and std's of each activity. 

After importing the data set I took found only the features that I wanted to import. I used the vector, featureswanted, for this string. I then used this vector to subset all further tables being read in so I only brough in the data that I wanted. Each gsub() function was used to make substitutions to variables, making them easier to read. 

The rest of the data was then read in, although being subset by the features wanted variable so that only the correct data was brough in. After merging all the data into one file, allData, the calculations were then completed for means of each value. 

Finally the write.table function was used to export the final .txt file.
