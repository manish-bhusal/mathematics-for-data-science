# Learn Statistics Concept

Statistics is like a big puzzle. Imagine you have a big box full of different colored blocks. Some blocks are red, some are blue, some are green, and so on.

Statistics is a way to figure out things about those blocks. Like, how many blocks are red? How many blocks are blue? Are there more red blocks or more blue blocks? Or maybe they are the same?

We use statistics to help us understand data, like the blocks in our box. We can use statistics to count things, to compare things, to make predictions, and to understand patterns.

For example, if you want to know how many blocks of each color you have, you would use statistics to count the number of red blocks, the number of blue blocks, and so on. If you want to know which color is the most common, you would use statistics to compare the number of red blocks to the number of blue blocks. And if you want to predict how many blocks of a certain color will be in the box in the future, you would use statistics to make that prediction.

So, statistics is like a tool that helps us understand data, like the blocks in our box, by counting, comparing and predicting.

# Descriptive Statistics Vs. Inferential Statistics

When you're doing data analysis, you are conducting experiment or you're taking numbers for a group of people or group of objects. So that is called a population. And when you're take into account the entire population in your data analysis process, it is called descriptive statistics. And when you take a few samples for your process & then you say this anylysis applies to the entire population, it is called inferential statistics.

Descriptive statistics is used to summarize and describe data. It helps us understand what the data looks like and what the main patterns and features are. For example, if you have a set of numbers that represent the heights of people in a group, you can use descriptive statistics to find the average height (mean) and the most common height (mode) and how much the heights vary(standard deviation) in that group. You can also use visual tools like histograms, box plots, etc to understand the distribution of data.

Inferential statistics, on the other hand, is used to make predictions or inferences about a larger population based on a sample of data. For example, if you survey a small group of people about their political views and want to know what the views of all people are, you can use inferential statistics to make predictions about the views of the entire population based on the views of the people in your sample. This is done by using statistical models to estimate population parameters from sample statistics.

So, descriptive statistics helps us understand what the data looks like, while inferential statistics helps us make predictions or inferences about a larger population based on a sample of data.

# Outlier

An outlier is a data point that differs significantly from other observations. A value that "lies outside"(is much smaller or larger) than most of the other values in a set of data. For example: 25, 29, 3, 32, 85, 33, 27, 28, both **3** and **85** are **Outliers**.

# Percentile

A percentile is a way of measuring where a particular value falls in relation to the rest of the values in a dataset. Percentiles divide a dataset into 100 equal parts and tell you which part of the dataset a particular value falls into.

For example, if you have a list of 100 students' test scores and you want to know what score is at the 75th percentile, that means 75% of the students scored below that value and 25% scored above it. If a student scored higher than 75th percentile, that student is better than 75% of the students.

Percentile is a commonly used measure in statistics and it is used to understand the distribution of a dataset. For example, if you want to know what the typical score is for a test, you can look at the 50th percentile, which is also called the median. The median is the middle value of a dataset, so half of the scores are above the median and half are below it.

Percentiles are also used in many other fields like finance, healthcare and many more. Percentiles can be used to understand how a particular value compares to other values in a dataset, which can be useful for making decisions or comparing different groups of data.

**The 25th percentile is also called the first quartile.**

**The 50th percentile is generally the median.**

**The 75th percentile is also called the third quartile.**

**The difference between the third and first quartiles is the interquartile range.**

**Formula to Calculate _Percentile:_**

Percentile = (Number of Values Below ???x??? / Total Number of Values) ?? 100

Value = Percentile / 100 ?? (n+1)

**Watch this video to understand [Percentile](https://www.youtube.com/watch?v=OES4fdLEHkw)**

# Quantiles

Quantiles are similar to percentiles in that they divide a dataset into equal parts and tell you where a particular value falls in relation to the rest of the values. However, unlike percentiles, which divide the dataset into 100 parts, quantiles divide the dataset into a specified number of parts.

For example, if you have a dataset of 100 values and you want to divide it into 4 parts, you would use quartiles. Quartiles are a type of quantile and they divide the dataset into 4 parts, or quarters. The first quartile (Q1) is the 25th percentile, the second quartile (Q2) is the median (50th percentile) and the third quartile (Q3) is the 75th percentile.

Similarly, if you want to divide a dataset into 5 parts, you would use quintiles. Quintiles divide the dataset into 5 parts and the first quintile is the 20th percentile, second quintile is 40th percentile and so on.

In general, quantiles are useful for understanding the distribution of a dataset and for comparing different groups of data. They can be used to identify outliers, or values that are significantly different from the rest of the values in the dataset. In addition, quantiles can also be used to identify the spread of the data, for example, if the difference between first and third quartile is large, it means the data is spread out.

In summary, quantiles are similar to percentiles in that they divide a dataset into equal parts and tell you where a particular value falls in relation to the rest of the values, but unlike percentiles, which divide the dataset into 100 parts, quantiles divide the dataset into a specified number of parts.

# Standard Deviation and Mean Absolute Deviation

Imagine you have a group of 10 numbers, like the ages of your friends in a class. The average of those numbers is called the mean.

The standard deviation is a measure of how spread out the numbers are from the average. For example, if all of your friends' ages are very close to the average age, the standard deviation will be small. But if some of your friends are much older or younger than the others, the standard deviation will be larger.

Mean Absolute Deviation (MAD) is another measure of how spread out the numbers are from the average. The MAD is found by taking the average of the absolute differences between each number and the mean. The difference between the two concepts is that the standard deviation is computed using the square of the differences while MAD uses the absolute value of the differences.

For example, let's say the ages of your friends in the class are: 8, 9, 8, 9, 10, 8, 7, 8, 9, 10. The mean is 8.5.

To find the standard deviation, first find the difference between each number and the mean. Then square each difference and add them all up. Finally, divide the sum by the number of numbers you started with (10) and take the square root of that number.

To find the MAD, first find the difference between each number and the mean. Then take the absolute value of each difference, add them all up and divide the sum by the number of numbers you started with (10).

# Why is standard deviation considered to be a better measure of spread when dealing with outliers?

Standard deviation is considered to be a better measure of spread than mean absolute deviation (MAD) in some cases because it is more sensitive to outliers.

An outlier is a number that is much larger or smaller than the other numbers in the group. For example, if all of your friends' ages were 8, 9, and 10, except for one who is 20 years old, that 20-year-old would be an outlier.

The standard deviation will be larger when there are outliers because it takes the square of the differences between each number and the mean, so the large differences caused by outliers will have a greater impact on the standard deviation than on the MAD.

On the other hand, MAD is less sensitive to outliers, because it only takes the absolute value of the differences between each number and the mean, so the large differences caused by outliers will have the same impact as small differences.

For example, let's say you have two groups of numbers:

**Group 1:** 1, 2, 3, 4, 5, 6, 7, 8, 9, 10

**Group 2:** 1, 2, 3, 4, 5, 100

The mean of both groups is the same, 5. But the standard deviation of group 2 is much larger than that of group 1 because of the outlier 100. The MAD of both groups is also the same, 4.5 which is the same for both group.

In conclusion, Standard deviation is a better measure of spread when you want to take into account outliers, while mean absolute deviation is a better measure when you want to ignore outliers.
