#recursive function
def factorial(n):
    if n==0 or n==1:
        return 1
    return n* factorial(n-1)
num=int(input("enter a value:")) 
value=factorial(num)
print(value)
..........output.............
enter a value: 6
720


#head recursion
def head(n):
    if n==0:
        return
    head(n-1)
    print(n)
num=int(input("enter a number"))
head(num)
..........output.............
enter a number 5
1
2
3
4
5



#head recursion
def head(n):
    if n==0:
        return
    print(n)    
    head(n-1)
num=int(input("enter a number"))
..........output.............
enter a number 5
5
4
3
2
1
head(num)
