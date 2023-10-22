Q2. Write a Python Program to find the squares of all the numbers in the given list of integers using
lambda and map functions.
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
ANS:= GIVEN LIST l=[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
        IN MAP FUNCTION USE
        def sq(x):
            return x**2
         list(map(sq,l))
       [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]    
       IN LAMBDA FUNCTION USE
       list(map(lambda x : x**2, l))
        [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
        
Q4 Write a python program using reduce function to compute the product of a list containing numbers from 1 to 25.
ANS: from functools import reduce
     l=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25]
     reduce(lambda x,y : x+y,l)
     325
     
Q5.Write a python program to filter the numbers in a given list that are divisible by 2 and 3 using the filter function.
[2, 3, 6, 9, 27, 60, 90, 120, 55, 46]
ANS:list(filter(lambda x : x% 2==0,l1))
    [2, 6, 60, 90, 120, 46]
    list(filter(lambda x : x% 3==0,l1))
    [3, 6, 9, 27, 60, 90, 120]
    
Q6.Q6. Write a python program to find palindromes in the given list of strings using lambda and filter
function.
['python', 'php', 'aba', 'radar', 'level']
    [4 TH FEB.ASSIGNMENT.md](https://github.com/Shwetakobal/Assignment-4-feb/files/13063321/4.TH.FEB.ASSIGNMENT.md)

    
