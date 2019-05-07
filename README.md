# Recursion-Python
    Recursion in Python

# importing sys for increasing recursionlimit
    import sys
# This will set limit (2000)
    sys.setrecursionlimit(2000)
# For cheaking recursionlimit
    print(sys.getrecursionlimit())  
# Just for count the recursion 
    i = 0
# define function greed(): 
    def greet():
    global i
    i+=1
    print('Hello', i)
    greet()
# Calling function    
    greet()
