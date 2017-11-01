# VBA Codes

Miscellaneous codes in VBA to solve specific problems

## Code 1
### What it solves
Generate combinations using 'n' categories each one with A(n) amount of items
### How must be the data
The categories must be in columns, where each row will be the items. It is not necessary any kind of sort or special arrangement.
Usually, this kind of data is associated with elements which can be classified in differents categories, and once into a category, it can be classified on different ways

### Exemple
_Sheet 1_
+-----------+-------------+-------------+-----+-------------+
| Elements  | Category C1 | Category C2 | ... | Category Cm |
+-----------+-------------+-------------+-----+-------------+
| Element 1 |      A1     |      B1     | ... |      X1     |
| Element 2 |      A2     |      B1     | ... |      X3     |
| Element 3 |      A2     |      B3     | ... |      X7     |
|     .     |      .      |      .      | .   |      .      |
|     .     |      .      |      .      |  .  |      .      |
|     .     |      .      |      .      |   . |      .      |
| Element n |      An     |      Bm     | ... |      Xk     |
+-----------+-------------+-------------+-----+-------------+

### Result
_Sheet 2_
A set of (N x M x ... x K) groups, built from combination of the categories
