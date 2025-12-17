  Q1 Solution  :
#1 : Desecriptive is used to summarize the characteristics of a dataset , such as findind the average or the most frequent value .Inferential allows us to make predictions about a large population based on smaller sample of data .

#2 : Confidence Intravel provides a range of values where we expect the true population parameter to fall . A 95% Confidence Interval means that if we repeat the same study 100 times , the true result will be in this range in 95 of those cases 

#3 : Correlation is a statistical indicator of the relationship between two variables , when one variable changes , so does the other . Casation means that the changes in one variable brings about in the other , there is a cause and effect relationship between variables . It is important to distinguish between them because two things can be related without one causing the other .

#4 : Probability Distribution is mathematical function that shows the probability of outcomes . Discrete examples : Binomial and poisson distributions , Continuous examples : Normal ( gaussain ) and exponential distribution .

#5 : Population is the entire group that we want to draw conclusion about , Sample is the specific group of the population that you will collect data from . We can calculate the mean and median for both groups.

#6 : Histogram is a graph that shows you the distribution of data points across a continuous range of numerical values , it shows distribution shape ( symmetric , skewed ) , idenifies outliers and center tendency.

#7 : Range gives you the spreed of the whole data set and measures the difference between the minimum value and maximum value  , The interquarlity range gives you the spreed of the middle half of the a data set and less affected by extreme values .

#8 : A frequency distribution is a way to organize data and see how many times each value occurs in a dataset , it is important because, it simplifies complex data set by organizing them in tables or histograms and helps identify patterns 
, trends and outliers in data . 

-----------------------------------------------------------------------------------------------------------------------------------------------

Q2 Solution :

1.  Mean is 5.8 
    Mode is 2 , 3 
    Median is 5 
    variance and standard deviation is high because the data is spreed out from 1 to 14

2.  If it is population the mean is the same , the variance and standard would change , we would divide by N in population ,In sample we divide by N-1 to get more accurate 

3.  It is right skewed distribution because it has a long tail on the right side , In the right skewed, the measures are pulled in the orded mean>median>mode

 --------------------------------------------------------------------------------------------------------------------------------------------------

Q3 Solution :

1. The distribution is left skewed Because the tail extends towards the lower on the left sude

2. It suggest a moderate to high spreed

3. If treated as population the variance and standrad would be lower because we divide by N instead of N-1

---------------------------------------------------------------------------------------------------------------------------------------------------

Q4 Solution :

1. True , False

2. Interpreter translate code line by line during execution , Compiler translate the whole code at once before running .

3. Slicing : A way to extract a part of a list using [ strat : stop : stop ]

4. Shallow Copy copies reference to nested object , while deep copy creats completly independent copies of all objects . A shallow code only copies the outer container , but not the inner object . If you modify a nested element in the copy , the original list will also change .

5. Filter() used to filter the element from the list based on the certain condition function if it true , map()  applies a function to each element in an iterable and returns a new iterable containing the results and list comprehension is a concise and poweful way to create new list by applying an expression to each item in existing iterable .

6. output is b)

7. Raise : To manual raise an error whenever you want , you decide what type of error and when it happens . Assert : To check if a condition is true while running the program ,if the condition is true the program continues, if the condition is false it raise an assertionError ans stops the program . Returning error codes : The function or program returns a nunber to indicate if an error occured , No excaption is raised , just value
Do not use assert to check user input , only for internal debugs

8. Encapsulation , Inheritance , polymorphism and Abstraction
   Sort() : A method that sorts the list in place . it modifies the original list and returns none . Sorted() A built in function that returns a new sorted list from any iterable , leaving the original data unchanged .

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Problem Solving :


n = 8
k = 5
count = 0
scores =[ 10,9,8,7,7,7,5,5 ]
goal = scores[k-1] 
for s in scores : 
 if s >= goal and s > 0 :
  count += 1
print(count)

-------------------------------
n = 4 
k = 2
count = 0
scores = [ 0, 0, 0, 0] 
goal = scores[k-1]
for s in scores :
 if s >= goal and s > 0 :
  count += 1
print(count)

 ----------------------------------
