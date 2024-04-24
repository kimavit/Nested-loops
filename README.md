Nested-loops.
======

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
-----
````ruby
total = 0
for n in range(1, 29):
    for k in range(1, 31):
        for m in range (1, 32):
            if 28 * n + 30 * k + 31 * m == 365:
                total += 1
                print('n =', n, 'k =', k, 'm =', m)
````
-----
