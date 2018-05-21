#### Exercise 2.1

```python
countries = open('./example_files/countries.txt', 'r')
lines = [line.rstrip().split(' -- ') for line in countries]
    
dict(lines)

```

