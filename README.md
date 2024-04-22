Nested-loops.
======

------
````ruby
num = int(input())
for i in range(1, num + 1):
    for j in range(1, 10):
        print(i, '+', j, '=', i + j)
    print()
````
-------
````ruby
n = int(input())
for i in range (1, n//2+2):
        print("*" * i)
for j in range (n//2, 0, -1):
        print("*" * j)
````
