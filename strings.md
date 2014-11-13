# A list of examples of string usages:

```
name = "neil young"
age = '71'
```

### get string's length:
```
len(name)
>>> 10
```

### String slicing:
```
[begin:end:step]
```
#### get a character in a string:
```
print name[0]
>>> n
print name[-1]
>>> g
```
### slice a sequence of characters:
```
print name[1:3]
>>> ei
print name[:2]
>>> ne
print name[1::2]
>>> elyug
print name[::2]
>>> ni on
print name[::-1]
>>> gnuoy lien

```

### String [concatenation](https://en.wikipedia.org/wiki/Concatenation)
```
name = 'Katniss'
age = 16
district = 'Distrcit 12'
sister = 'Prim'
```

#### primitive concatenation:
```
sentence = 'This is ' + name + ', she is ' + str(age) + ' years old. She lives in ' + district + '.'
print sentence
>>> This is Katniss she is 16 years old. She lives in Distrcit 12.
```

#### old style formatting:
```
sentence = 'This is %s she is %d years old. She lives in %s.' %(name, age, district)
print sentence
>>> This is Katniss she is 16 years old. She lives in Distrcit 12.
```

#### modern string formatting:
```
sentence = 'This is {}, she is {} years old. She lives in {}.'.format(name, age, district)
print sentence
>>> This is Katniss, she is 16 years old. She lives in Distrcit 12.
```

#### another advantage of the modern string formatting:

##### when we want to use the same variable several times in a sentence.
```
sentence = '''
This is {0}, she is {1} years old.
{0} lives in {2}.
{0} little sister is {3}.
'''.format(name, age, district, sister)
print sentence

>>> This is Katniss, she is 16 years old.
    Katniss lives in Distrcit 12.
    Katniss little sister is Prim.

```

### String methods:
```
name = 'Neil Young'

print name.upper()
>>> NEIL YOUNG
print name.lower()
>>> neil young
print name.title()
>>> Neil Young
print name.capitalize()
>>> Neil young
name = name.title()
print name
>>> Neil Young
print name.swapcase()
>>> nEIL yOUNG
```

### special questions about strings:
```
print age.isdigit()
>>> True
print age.isalpha()
>>> False
print name.isalpha()
>>> False
print name[0].isalpha()
>>> True
print name[4].isspace()
>>> True
```