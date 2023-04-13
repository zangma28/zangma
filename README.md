import random

with open("numbers.txt", "r") as f:  
    numbers = [int(line.strip()) for line in f.readlines()]

random_number = random.choice(numbers)  
print(random_number)  
