# A list of examples of list usages:

```
# this is a list of the known Animal Liberation Front (ALF) activists that were murdered or killed.
# Source: http://www.sourcewatch.org/index.php?title=Environmental_and_animal_activists_injured_or_killed
alf_murdered = ['Valmir Mota de Oliveira',
                'Bartolomeu Morais da Silva',
                'David "Gypsy" Chain',
                'Dr. Karel Van Noppen',
                'Jill Phipps',
                'Tom Worby',
                'Mike Hill',
                'Chico Mendes',
                'Fernando Pereira',
                'Dian Fossey',
                'William Sweet']
```

### get list's length:
```
len(alf_murdered)
>>> 11
```

### List slicing:
#### [begin:end:step]
#### get an item in a list:
```
print alf_murdered[0]
>>> Valmir Mota de Oliveira
print alf_murdered[-1]
>>> William Sweet
```
### slice a sequence of list items:
```
print alf_murdered[1:3]
>>> ['Bartolomeu Morais da Silva', 'David "Gypsy" Chain']
print alf_murdered[:2]
>>> ['Valmir Mota de Oliveira', 'Bartolomeu Morais da Silva']
print alf_murdered[1::2]
>>> ['Bartolomeu Morais da Silva', 'Dr. Karel Van Noppen', 'Tom Worby', 'Chico Mendes', 'Dian Fossey']
print alf_murdered[::2]
>>> ['Valmir Mota de Oliveira', 'David "Gypsy" Chain', 'Jill Phipps', 'Mike Hill', 'Fernando Pereira', 'William Sweet']
print alf_murdered[::-1]
>>> ['William Sweet', 'Dian Fossey', 'Fernando Pereira', 'Chico Mendes', 'Mike Hill', 'Tom Worby', 'Jill Phipps', 'Dr. Karel Van Noppen', 'David "Gypsy" Chain', 'Bartolomeu Morais da Silva', 'Valmir Mota de Oliveira']
```

### Sort a list:
#### Default sort is according to lexical order:
```
alf_murdered_sorted = sorted(alf_murdered)
print alf_murdered_sorted
>>>['Bartolomeu Morais da Silva', 'Chico Mendes', 'David "Gypsy" Chain', 'Dian Fossey', 'Dr. Karel Van Noppen', 'Fernando Pereira', 'Jill Phipps', 'Mike Hill', 'Tom Worby', 'Valmir Mota de Oliveira', 'William Sweet']
```

#### For a better understanding, let's see how it works with lists of numbers and strings:
```
l = ['1', '2', '5', '10', '20', '50', '100']
print sorted(l)
>>> ['1', '10', '100', '2', '20', '5', '50']

numbers = [1, 2, 5, 10, 20, 50, 100]
print sorted(numbers)
>>> [1, 2, 5, 10, 20, 50, 100]
```
