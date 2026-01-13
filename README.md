# ASCII-2
c = input("Enter a character: ")  
print("The ASCII value of '" + c + "' is",ord(c))  
n=int(input("Enter the Limit:"))
for i in range(1,n+1):
    for k in range(n-i,0,-1):
        print('',end='')
    for j in range(1,i+1):
        print("*",end='')
    print("")
OUTPUT:
Enter a character: *
The ASCII value of '*' is 42
Enter the Limit:6
*
**
***
****
*****
******
