total_sum = 0

print("Enter 10 numbers:")

for i in range(10):
    number = float(input(f"Enter number {i+1}: "))
    total_sum += number

print("\nThe sum of the 10 numbers is:", total_sum)
