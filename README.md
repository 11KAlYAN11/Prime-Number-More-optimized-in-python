# Prime-Number-More-optimized-in-python
the most optimized prime number program in python





from math import sqrt      
for i in range(1,100000):
    k = int(sqrt(i))
    for j in range(2,k):
        if(i%j == 0):
            break
    else:
        print(i,end=" ")

