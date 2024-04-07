# Q.15
n = int(input("Enter a number: "))

sum_of_cubes = sum(int(digit)**3 for digit in str(n))

if sum_of_cubes == n:
    print(n, "is an Armstrong number")
else:
    print(n, "is not an Armstrong number")
