# Project1_Repository

In this project we tried to decision with the help of machine learning either the coupons had sent by Amazon is accepted or not by tht drivers.

At first I did the number of rows and columns check up and grap a summary of the dataset we have given. The dataset has 12684 entries and 26 columns. The I have checked 
all missing values and other special chacter that cause a problem for the machine. From the total survey, the "Car" column has 12576 from 12684 missing value. This is more than 99% missing values. Since this column has a huge number of missing values, it is quite had to fill it and give to machine. probablly,our result will affect by this decision. So,I decided to drop the column. 

For the others such as Bar,coffeeHouse,CarryAway,RestaurantLessThan20,Restaurant20To50, since each column has below 2% missing values, I fill it the missing values with the highest counts for each coupons.

After I cleaned up all the missing datas, I calculated the total numbers of coupons accepted by the drivers. Out of the total numbers coupons from the this survey, 7210 coupons are acepted. When we see in percentage 56.84%. Still there is a good indication for amazon about the coupons they have sent. Then, I did some graphical represntation, to visualise more details about the datas.

Last, I just graped only for the bar coupons, to see how it affects by the attributes. I did compasion acceptance rate between those who went to a bar 3 or fewer times a month to those who went more. So, I get that the total number of bar coupons accepted by those who went to bar less than 3 or fewer is 6323 and total number of bar coupons accepted by those who went to bar more times is 887. This is more 12% coupons where accepted by those who went to bar less than 3 or fever than those who went to bar more times.

I did also other comparsion the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. More 70% the bar coupons are accepted by those who go to the bar less than one than drivers who go to a bar more than once a month and are over the age of 25. More 27% acceptance rate of  drivers who had an occupations other than farming, fishing, or forestry than drivers who go to bars more than once a month and had passengers that were not a kid.

Last conclusion:
From the total survey, 2017 bar coupons were sent to the drivers. Only 827 or 41% were accpted and more than 59% were rejected. From the total accepted bar coupons, 674 were accpted by drivers who went to bar less than 3 or fever and rest (153) accepted by drivers who went to bar more.



