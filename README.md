# Project1_Repository

In this project I try to make a decision to know with the help of machine learning whether the coupons sent by Amazon are accepted or not by the drivers.

First I did the number of rows and columns check up and grab a summary of the dataset we have given. The dataset has 12684 entries and 26 columns. Then, I have checked
all missing values and other special characters that are problematic for the machine. From the total survey, the "Car" column has 12576 missing values. More than 99% are missing values. Since this column has a huge number of missing values, it is quite hard to fill it and give it to the machine. probably,our result will be affected by this decision. So,I decided to drop the column.

For the other columns such as Bar,coffeeHouse,CarryAway,RestaurantLessThan20,Restaurant20To50, since each column has below 2% missing values, I fill it with the missing values which have the highest counts for each coupon.

After I cleaned up all the missing datas, I calculated the total numbers of coupons accepted by the drivers. Out of the total number of coupons from this survey, 7210 coupons are accepted. This is 56.84%. Still there is a good indication for amazon about the coupons they have sent. Then, I did some graphical representation, to visualize more details about the datas.

Last, I just grasped only for the bar coupons, to see how this affects attributes for the coupon. I did compassion acceptance rate between those who went to a bar 3 or fewer times a month to those who went more. So, I get that the total number of bar coupons accepted by those who went to bar less than 3 or fewer is 6323 and total number of bar coupons accepted by those who went to bar more times is 887. This is more 12% coupons were accepted by those who went to bar less than 3 or fever than those who went to bar more times.

I also did another comparison of the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to all others. More 70% the bar coupons are accepted by those who go to the bar less than one than drivers who go to a bar more than once a month and are over the age of 25. More 27% acceptance rate of  drivers who had an occupations other than farming, fishing, or forestry than drivers who go to bars more than once a month and had passengers that were not a kid.

Last conclusion:
From the total survey, 2017 bar coupons were sent to the drivers. Only 827 or 41% were accepted and more than 59% were rejected. From the total accepted bar coupons, 674 were accepted by drivers who went to bar less than 3 or fever and rest (153) accepted by drivers who went to bar more.




