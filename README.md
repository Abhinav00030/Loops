# 1. For loop with a range
print("1. For loop with range:")
for i in range(5):
    print(f"Iteration {i}")

# 2. While loop
print("\n2. While loop:")
count = 0
while count < 5:
    print(f"Count is {count}")
    count += 1

# 3. For loop with a list
print("\n3. For loop with a list:")
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(f"Current fruit: {fruit}")

# 4. Nested loop
print("\n4. Nested loop:")
for i in range(3):
    for j in range(2):
        print(f"i = {i}, j = {j}")

# 5. Loop with break statement
print("\n5. Loop with break:")
for num in range(10):
    if num == 5:
        break
    print(f"Number: {num}")

# 6. Loop with continue statement
print("\n6. Loop with continue:")
for num in range(5):
    if num == 2:
        continue
    print(f"Number: {num}")

# 7. While loop with else
print("\n7. While loop with else:")
n = 0
while n < 3:
    print(n)
    n += 1
else:
    print("Loop completed!")
