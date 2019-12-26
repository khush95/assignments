# assignments
#factorial
num =4
factorial = 1
if num < 0:
    print("sorry, factorial does not exits")
elif num ==0:
    print("the fact of o is 1")
else:
    for i in range(1,num+1):
        factorial = factorial*i
    print("the fact of",num,"is",factorial)
    
