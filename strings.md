# A list of examples of integer usages:

name = "neil young"
age = '71'

### get string's length:
```
len(name)
>>> 10
```

### String slicing:
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
gnuoy lien

```

### String methods:
```
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