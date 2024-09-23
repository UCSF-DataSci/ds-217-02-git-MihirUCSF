# Assignment 1 
# Mihir Kalyanthaya

print("Hello, Data Science!")

total_sum=0
for i in range(1000):
    if i%3==0 or i%5==0:
        total_sum+=i
print("Sum of all the multiples of 3 or 5 below 1000:", total_sum)
