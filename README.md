# to check whether given number is prime or not
 
num = int(input("enter a number: "))
i = 2  
count = 0
while i <= num // 2:
    if num % i == 0:
        count = count + 1
        break
    i = i + 1
    
if count == 0:
    print("The entered number {} is a PRIME number".format(num))
else:
    print("The entered number {} is not a PRIME number".format(num))


Output 1:
enter a number:13
The entered number 13 is a PRIME number
