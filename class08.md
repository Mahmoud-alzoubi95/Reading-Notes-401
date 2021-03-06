# List Comprehensions in Python


* List comprehensions provide a concise way to create lists.

* The list comprehension always returns a result list.

**Without** List comprehension
```
new_list = []
for i in old_list:
    if filter(i):
        new_list.append(expressions(i))
```

**With** List comprehension

`new_list = [expression(i) for i in old_list if filter(i)]`

## Syntax :
`[ expression for item in list if conditional ]`


## using If with list comprehension
* Genearal Formula:

*result* = [*transform* *iteration* *filter* ]
* example :

new_range = [i * i for i in range(5) if i % 2 == 0]
