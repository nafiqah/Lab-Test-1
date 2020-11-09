# Lab-Test-1
Question 1
def countBits(n): 
    count = 0
    while (n): 
        count += 1
        n >>= 1
          
    return count 

i = 24
print(countBits(i)) 


Question 2
def string_frequency(str1):
    dict = {}
    for n in str1:
        keys = dict.keys()
        if n in keys:
            dict[n] += 1
        else:
            dict[n] = 1
    return dict
print(string_frequency('an apple is not a tomato"'))

Question 3
def word_count(str):
    counts = dict()
    words = str.split()

    for word in words:
        if word in counts:
            counts[word] += 1
        else:
            counts[word] = 1

    return counts

print( word_count('"I have Python exam'))

question 4(a)
def print_arguments(a,b,c):
   x=c*10
   y=a+b
   return x,y

sums = print_arguments(3,4,2)
print(sums)

question 4(b)
#define function sum
def mul():
    fi = input("first number: ")
    s1 = 2
    ht = int(fi) * (s1)
    return ht

#main program
print("Enter 2 Numbers")
rv =mul()
print("Multiply of these numbers by 2 is ", rv)

