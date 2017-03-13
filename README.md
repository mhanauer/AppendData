# AppendData
#First we need to change the names of the columns to be the same thing.
names(mccsc5) = c("PD", "Category")
names(rbbcsc5) = c("PD", "Category")

#Then we need to append the two data sets together.  We can do that using the rbind function.
both = rbind(mccsc5, rbbcsc5); both
