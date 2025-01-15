# This script reads numbers from number.txt and sums them.

with open('number.txt', 'r') as file:
    numbers = file.readlines()
    total = sum(int(num.strip()) for num in numbers)
    print(total)
