# machinelearning
ML is the subset of AI that enables system to learn automatically from the data by analysis on the basis of pre defined algo which help to predict and make improve pattern of data for desired outcome without explicilty using the coding structure . It involves training algo on data to identfiy patterns , relationships and decision mahing processess.
Key components of ML
1 . Data
2 . Algo
3. Model Training
4. Prediction and decision making

Type of ML
1. Supervised Learning -> work on lablled data
2. Unsupervised Learning -> identify and orgainse unstructureed data into labled form 
3. Reinforement Learning -> Learning through trials and error so system work on env.

Goals of ML
1. Predicition
2. Classification
3. Clustering
4. Decision making
5. Optimization

Mathematical statistics for ML(basic level)
1. Mean - average value
2. Median - mid value after organizing data in asending order
3. Mode - most common value
4. Standard Devition - is the numver that describe the how value spread out from median value

   Standard deviation is a number that describes how spread out the values are.

   A low standard deviation means that most of the numbers are close to the mean (average) value.

   A high standard deviation means that the values are spread out over a wider range.

   example :
   Example: This time we have registered the speed of 7 cars:
    speed = [86,87,88,86,87,85,86]

The standard deviation is: 0.9
Meaning that most of the values are within the range of 0.9 from the mean value, which is 86.4.

Let us do the same with a selection of numbers with a wider range:
speed = [32,111,138,28,59,77,97]

The standard deviation is: 37.85
Meaning that most of the values are within the range of 37.85 from the mean value, which is 77.4.

As you can see, a higher standard deviation indicates that the values are spread out over a wider range.
![image](https://github.com/user-attachments/assets/6e67dea3-8313-4858-bd42-90f9dc353c83)


Variance
Variance is another number that indicates how spread out the values are.

In fact, if you take the square root of the variance, you get the standard deviation!

Or the other way around, if you multiply the standard deviation by itself, you get the variance!

To calculate the variance you have to do as follows:

1. Find the mean:

(32+111+138+28+59+77+97) / 7 = 77.4

2. For each value: find the difference from the mean:

 32 - 77.4 = -45.4
111 - 77.4 =  33.6
138 - 77.4 =  60.6
 28 - 77.4 = -49.4
 59 - 77.4 = -18.4
 77 - 77.4 = - 0.4
 97 - 77.4 =  19.6

3. For each difference: find the square value:

(-45.4)2 = 2061.16
 (33.6)2 = 1128.96
 (60.6)2 = 3672.36
(-49.4)2 = 2440.36
(-18.4)2 =  338.56
(- 0.4)2 =    0.16
 (19.6)2 =  384.16

4. The variance is the average number of these squared differences:

(2061.16+1128.96+3672.36+2440.36+338.56+0.16+384.16) / 7 = 1432.2

Luckily, NumPy has a method to calculate the variance:
![image](https://github.com/user-attachments/assets/9eb1772b-2756-4fd6-82cc-47a4307dcce8)



