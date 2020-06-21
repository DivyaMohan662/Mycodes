# Mycodes
n=int(input("enter n:"))
sum=0
a=0
b=1
num=1
for num in range(1,n):
    print(sum,end=" ")
    num=num+1
    a=b
    b=sum
    sum=a+b
    
