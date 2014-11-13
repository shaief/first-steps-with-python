# A list of examples of common sequences operations:
### A sequence can be:
* a string
* a list
* a tuple

##### strings and tuples are immutable
##### lists are mutable (items in a list can be replaced)

### to create a list from a string, we use split()
```
phrase = 'No one is free until everyone is free!'
```
As you can see, phrase is a variable that holds a string. How can we split the sentence to the words building it?
```
phrase_list = phrase.split()
print phrase_list
>>> ['No', 'one', 'is', 'free', 'until', 'everyone', 'is', 'free!']
```
The basic syntax for  ```split()``` will split the sentence at whitespaces (space, tabs, newline).
 
### to get sequence's length we use len():
```
len(phrase)
>>> 79
len(phrase_list)
>>> 8
```

### to create a string from items in a list, we use join()
```
post_title = 'The most important text you will read'
slug_list = post_title.split()
slug = '_'.join(slug_list)
print slug
>>> The_most_important_text_you_will_read
```

### What happens when we cast string to list?
```
phrase_casted_to_list = list(phrase_list[0])
print phrase_casted_to_list
>>> ['N', 'o']
```
### and when we cast list to string?
```
list_casted_to_string = str(phrase_casted_to_list)
print list_casted_to_string
"['N', 'o']"
```
### Sequence slicing (the same for all sequences):
```
[begin:end:step]
```

#### get an item in a sequence:
```
print phrase[0]
>>> N
print phrase[-1]
>>> !
print phrase_list[0]
>>> No
print phrase_list[-1]
>>> free!
```
