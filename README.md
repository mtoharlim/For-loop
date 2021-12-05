# For-loop
> Range(1, 30)

```
print(list(range(1, 30)))

```
## Output
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29]

# Can you compute all multiples of 3, 5

```
for i in range(1, 31):
    if i % 3 == 0:
        print(i)
    elif i % 5 == 0:
        print(i)
   
```
### Output multiples
3
5
6
9
10
12
15
18
20
21
24
25
27
30

# Total of Multiples

```
total3 = 0
for i in range(1, 8):
    if i % 3 == 0:
        total3 += i
print(total3)

```

### Output

9
