# an example for a while True loop. The loop breaks when the user enters an empty string ('')
```
while True:
    user_input = raw_input('>')  # remember that if you like a variable to change, it has to be in the while block 
    if not user_input:
        print 'bye'
        break

>>> >hi
>>> >
>>> bye

```
