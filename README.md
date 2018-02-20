# Primitive Types
* Created 20-02-2018

## Be Familiar With
* The bit-wise operators. `&` (AND), `|` (OR), `>>` (shift right), `<<` (shift left), `~` (binary negation) `^` (XOR)
* The key methods for numeric types `abs()`, `math.ceil(2.17)`, `math.floor(3.14)`, `min()`, `max()`, `pow()`, `math.sqrt()`
* Know how to interconvert integers and strings, `str(42)`, `int('42')`, (you can do the same thing between floats and strings
* Unlike integers, floats are not infinite precision, and it's convenient to refer to `float('inf')` and `float('-inf')`. These values are comparable ton integers and can be used to create pseudo max-int and pseudo min-int.
* When comparing floating point values, consider using `math.isclose()`, it is robust when comparing very large values, and can handle both absolute and relative differences.
* The key methods in `random` are `random.randrange(28)`, `random.randint(8, 16)`, `random.random()`, `random.shuffle(A)`, and `random.choice(A)`