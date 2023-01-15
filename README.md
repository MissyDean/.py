"# .py" 
"# .py" 
Question 1
Write a function to print "hello_USERNAME!" USERNAME is the input of the function. The first line of the code has been defined as below.

    def hello_name(user_name):
name="USERNAME"
print('"hello_ ' + name + '"')
                
Question 2
Write a python function, first_odds that prints the odd numbers from 1-100 and returns nothing

    def first_odds():
list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19,
20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38,
39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 
58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 
76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 
94, 95, 96, 97, 98, 99, 100]
i = 0
while(i < len(list1)):
    if list1[i] % 2 != 0:
        print(list1[i], end=" ")
    i += 1
                
Question 3
Please write a Python function, max_num_in_list to return the max number of a given list. The first line of the code has been defined as below.

  def max_num_in_list( list ):  
    max = list[ 0 ]  
    for a in list:  
        if a > max:  
            max = a  
    return max  
print(max_num_in_list([6, 12, 28, 60])) 
                
Question 4
Write a function to return if the given year is a leap year. A leap year is divisible by 4, but not divisible by 100, unless it is also divisible by 400. The return should be boolean Type (true/false).

    def is_leap():
    leap = False
    if (year % 4 == 0 and year % 100 != 0) or year % 400 == 0:
        leap = True
    return leap
                
Question 5
Write a function to check to see if all numbers in list are consecutive numbers. For example, [2,3,4,5,6,7] are consecutive numbers, but [1,2,4,5] are not consecutive numbers. The return should be boolean Type.

    def checkConsecutive(l):
    n = len(l) - 1
    return (sum(np.diff(sorted(l)) == 1) >= n)
