# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples

### Codeblocks

Some `code` goes here.

### Plain codeblock

A plain codeblock

```
Some code here
def myfunction()
// some comment
```

### Code for a specific language

Some more code with the `py` at the start:

``` py
from datetime import datetime

def get_current_time()
    print(datetime.now())
```

#### With a title
``` py title="get_current_day.py"
from datetime import date

def get_current_day()
    return date.today()
```

#### with line numbers
``` py title="times_table.py" linenums="1"
from rich import pretty, print
pretty.install()

def times_table(num, limit):
    res = [num * idx for idx in range(1, limit+1)]
    return res
```

#### with line numbers and highlighted lines
``` py title="times_table.py" linenums="1" hl_lines="4 5 6"
from rich import pretty, print
pretty.install()

def times_table(num, limit):
    res = [num * idx for idx in range(1, limit+1)]
    return res
```

## Icons and Emojis

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }