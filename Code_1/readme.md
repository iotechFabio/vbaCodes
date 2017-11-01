## Code 1
### What it solves
Generate a list of all possible combinations using 'n' columns, each one with 'm' items.

### How must be the data
The categories must be in columns, where each row will be the items. It is not necessary any kind of sort or special arrangement.
Usually, this kind of data is associated with elements which can be classified in differents categories, and once into a category, it can be classified on different ways.

### Exemple
_Sheet 1_

| Elements  | Category C1 | Category C2 | ... | Category Cm |
|   :---:   |    :---:    |    :---:    |:---:|    :---:    |
| Element 1 |      A1     |      B1     | ... |      X1     |
| Element 2 |      A2     |      B1     | ... |      X3     |
| Element 3 |      A2     |      B3     | ... |      X7     |
|     .     |      .      |      .      |  .  |      .      |
|     .     |      .      |      .      |  .  |      .      |
|     .     |      .      |      .      |  .  |      .      |
| Element n |      An     |      Bm     | ... |      Xk     |

### Result
A set of (N x M x ... x K) groups, built from combination of the categories

_Sheet 2_

| A       | B            | C         | D         | E   | F         |
|  :---:  |     :---:    |   :---:   |   :---:   |:---:|   :---:   |
| Group 1 | A1 B1 ... X1 | Element 1 | Element l | ... |           |
| Group 2 | A1 B1 ... X3 | Element j |           | ... |           |
| Group 3 | A2 B1 ... X7 | Element k | Element m | ... | Element o |
|    .    |       .      |     .     |     .     | ... |     .     |
|    .    |       .      |     .     |     .     | ... |     .     |
| Group X | A2 B1 ... X3 | Element 2 | Element n | ... |           |
|    .    |       .      |     .     |     .     | ... |     .     |
|    .    |       .      |     .     |     .     | ... |     .     |
| Group Y | A2 B3 ... X7 | Element 3 | Element p | ... | Element q |
|    .    |       .      |     .     |     .     | ... |     .     |
|    .    |       .      |     .     |     .     | ... |     .     |
| Group Z | Ax By ... Xz |           |           |     |           |
