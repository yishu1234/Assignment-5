#Q1 Program to reverse the string.

a = input('Enter the string to reverse\n')
print (a[::-1])

#Q2 Python Program to Print all Numbers in a Range Divisible by a Given Number.

a=int (input('Enter the lower value of range\n'))
b=int (input('Enter the last value of range\n'))
n=int(input('Enter the no. which is divisible to the given range\n'))
print (' all Numbers in a Range Divisible by a',n,':-')
for i in range(a,b+1):
    if (i%n==0):
        print(i)
print('end')  
  
#Q3 Program to calculate the area of a triangle using heron’s formula.
a = int(input('Enter the first side\n'))
b = int(input('Enter the second side\n'))
c = int(input('Enter the third side\n'))
s = (a+b+c)/2
if (a+b>c and a+c>b and c+b>a):
    area = (s*(s-a)*(s-b)*(s-c))**0.5
    print ('Area of the triangle ',round(area,2))
else:
    print('area is not possible')

#Q4 Python program to print star pattern

n= int(input('enter the no. of columns of star pattern to print \n'))
print ('===== The Star Pattern =====')
for i in range(1,n+1):
    print(i*'*')
for i in range(n-1,0,-1):   
    print (i*'*')

#Q5 python program to print abcd pattern
rows = int(input("Enter Right Triangle Consecutive Alphabets Rows = \n"))
print("====The Right Triangle of Consecutive Alphabets Pattern====")
k = ord('A')
for i in range(rows):
    for j in range (i+1):
        print (chr(k), end=" ")
        k+=1
        if (k>=91):
            k-=26
    print()      


#Q6 Write a python program to print the prime numbers for a user input range.

lower = int(input("Enter the lower value:\n"))
upper = int(input("Enter the upper value:\n"))
print ('The prime no. between ',(lower, upper),'are')
for number in range(lower,upper+1):
    if number>1:
        for i in range(2,number):
            if (number%i)==0:
                break
        else:
            print(number)

#Q7 Write a python program to find the numbers which are multiple of 7 and divisible by 11 in the range 1-500.

print ('The numbers which are multiple of 7 and divisible by 11 in the range 1-500 is')
for i in range(0,500):
    if (i%7==0 and i%11==0):
      print (i)
    else :
        continue

#Q8

lst = []
positive_numbers = set()
negative_numbers = set()
odd_numbers = set()
even_numbers = set()
print ('Enter the 10 no. for list')
for i in range(0,10):
    print ('Enter the', i+1,'no. for list')
    n = int(input())
    lst.append(n)  # adding the element
print ('list entered',lst)
for i in lst:
    if (i>0):
        positive_numbers.add(i)
    if (i<0):
        negative_numbers.add(i)
    if (i%2!=0) :   
        odd_numbers.add(i)
    if (i%2==0) :
        even_numbers.add(i)  
print ("positive no. \n", positive_numbers)
print ('negative no.\n', negative_numbers)
print ('odd no.\n', odd_numbers)
print ('even no.\n', even_numbers)
number_occurs= dict()
for i in lst:
    if i in number_occurs:
        number_occurs[i]+=1
    else:
        number_occurs[i]=1
print('No. of occurrence is',number_occurs)

#Q9 Write a program to count the number of occurrences of each word in the list(List entered by the user).

str = input('Enter the sentence :\n')
sentence = dict()
words = str.split()
for word in words:
    if word in sentence:
        sentence[word]+=1
    else:
        sentence[word] = 1
print (sentence)      


