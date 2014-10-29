# A list of examples of common for loops:

the basic syntax of `for` loops is:
```
for `variable` in `sequence`:
    do something
```

let's say we have a list of numbers called `numbers`:
```
numbers = [1, 2, 3, 4, 5]
```

now we would like to run through the list and perform some operations on it. Let's start with `print`:

```
for number in numbers:
    print number
>>> 1
    2
    3
    4
    5
```

now let's create another variable `sum`:
```
sum = 0
for number in numbers:
    sum += number  # remember that sum += number is just like: sum = sum + number
print sum
```

we can also create a list of numbers using `range()`:
```
numbers = range(5)  # ==> [0, 1, 2, 3, 4]
```

```
numbers = range(1, 5)  # ==> [1, 2, 3, 4]
```

and we can also run the `for` loop this way:
```
for number in range(5):
    print number
>>> 0
    1
    2
    3
    4
```

BUT - don't use range for that! use xrange() instead!
```
for number in xrange(5):
    print number
>>> 0
    1
    2
    3
    4
```


we can also run a `for` loop on a list of strings:

```
languages = ['python', 'perl', 'ruby']
for language in languages:
    print language.capitalize()
>>> Python
    Perl
    Ruby
```

and what if we want to have the index as well?
let's use `enumerate()`:
```
languages = ['python', 'perl', 'ruby']
for i, language in enumerate(languages):
    print i, language.capitalize()
>>> 0 Python
    1 Perl
    2 Ruby
```
