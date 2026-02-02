# -program-to-find-the-sum-of-first-n-even-numbers.-
n=int(input("Enter the limit:"))
s=0
for i in range(1,n+1,2):
    s=s+i
print("The sum is:",s)

OUTPUT:

Enter the limit:10
The sum is: 25
