# Numbers

- repr()
- str()
- print()


1 == 2 < 3

1 == 2 and 2 < 3

math
- math.floor()  // towards bottom
- math.trunc() // towards zero


0o20 - octal (8)
0xff - hexa (16)
0b1000 - binary (2)

oct()
hex()
bin()
int( '2', 8)

random
random.random()
random.randint( 1, 10)
random.choice([])
random.shuffle()

from decimal import Decimal
Decimal('0.1') + Decimal('0.1') + Decimal('0.1')
from fractions import Fractions
myfrc = Fraction(2,7)

type()

#############################################

# Strings
'', "", """ """
-slice
>>> num_list = "0123456789"
>>> num_list[:]
'0123456789'
>>> num_list[3:] 
'3456789'
>>> num_list[:7] 
'0123456'
>>> num_list[0:7:2] 
'0246'
>>> num_list[0:7:3] 
'036'

- .lower()
- .upper()
- .strip()
- .replace("to be replace", "from which it should be replaced")
- .split(", ") // in list
- .find("")
- .count("")
- placeholders {}
- .format("") // values which should be filled by placeholders
- " ".join()
- .len()
- r"" // raw string
- in

# List
- can do slicing
- .append() // at last
- .pop() // delete from last
- .remove()
- .insert(position, "What to add")
- .copy()
- list comprehension
squared_nums = [x**2 for x in range(10)] 
>>> print(squared_nums)

# Dictionary
- .get("")
- len()
- .pop("key")
- .popitems() // delete from last
- del name[]
- .copy()
{{}, {}, {}}
- .clear()
- dict.fromkeys(keys, value)

# tuple
list -> mutable
tuple -> immutable
- slicing
- len()
- .count()




