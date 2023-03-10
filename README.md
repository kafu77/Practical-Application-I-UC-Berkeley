# Project1_Repository

The goal of the project is to use machine learning to predict whether drivers will accept the coupons sent by Amazon. 

Dropping the "Car" column was a good decision since it had a huge number of missing values. Imputing missing values could have led to biased results and inaccurate predictions. By dropping the column, you ensured that the remaining data is clean and can be used for further analysis. It is always important to check for missing values and other inconsistencies in the dataset before performing any analysis to ensure accurate results.
For the other columns such as Bar,coffeeHouse,CarryAway,RestaurantLessThan20,Restaurant20To50, since each column has below 2% missing values, I fill it with the missing values which have the highest counts for each coupon.

After I cleaned up all the missing datas, I calculated the total numbers of coupons accepted by the drivers. Out of the total number of coupons from this survey, 7210 coupons are accepted. This is 56.84%. Still there is a good indication for amazon about the coupons they have sent. Then, I did some graphical representation, to visualize more details about the datas.

Last, I just grasped only for the bar coupons, to see how this affects attributes for the coupon. I did compassion acceptance rate between those who went to a bar 3 or fewer times a month to those who went more. So, I get that the total number of bar coupons accepted by those who went to bar less than 3 or fewer is 6323 and total number of bar coupons accepted by those who went to bar more times is 887. This is more 12% coupons were accepted by those who went to bar less than 3 or fever than those who went to bar more times.

I also did another comparison of the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to all others. More 70% the bar coupons are accepted by those who go to the bar less than one than drivers who go to a bar more than once a month and are over the age of 25. More 27% acceptance rate of  drivers who had an occupations other than farming, fishing, or forestry than drivers who go to bars more than once a month and had passengers that were not a kid.

Last conclusion:
From the total survey, 2017 bar coupons were sent to the drivers. Only 827 or 41% were accepted and more than 59% were rejected. From the total accepted bar coupons, 674 were accepted by drivers who went to bar less than 3 or fever and rest (153) accepted by drivers who went to bar more.




