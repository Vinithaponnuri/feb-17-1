PROGRAMME:
a = int(input(" Please Enter Value : "))
sum_even=0
sum_odd= 0
 
for number in range(a, 10+1):
    if(number % 2 == 0):
        sum_even = sum_even + number
    else:
        sum_odd = sum_odd + number
 
print("The Sum of Even Numbers from 1 to {0} = {1}".format(number, sum_even))
print("The Sum of Odd Numbers from 1 to {0} = {1}".format(number, sum_odd))
OUTPUT:
Please Enter Value : 2
The Sum of Even Numbers from 1 to 10 = 30
The Sum of Odd Numbers from 1 to 10 = 24
