#### Exercise 2.1

```python
countries = open('./example_files/countries.txt', 'r')
lines = [line.rstrip().split(' -- ') for line in countries]
    
dict(lines)

```

#### Exercise 2.2

for key in word_counts:
    if word_counts[key] >= 7:
        print(f'{key} => {word_counts[key]}')


#### Exercise 2.3
list_keys = list(word_counts.keys())
list_keys.sort() 

for key in list_keys:
    print(key, word_counts[key])