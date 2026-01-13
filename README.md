# finding-second-largest-number
n = int(input("Enter the limit: "))
small = int(input("Enter 1 th number: "))

for i in range(2, n + 1):
    a = int(input(f"Enter {i} th number: "))
    if a < small:
        small = a

print("Smallest number is:", small)
