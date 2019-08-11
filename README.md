### docopt
---
https://github.com/docopt/docopt

http://docopt.org/

```py
from docopt import docopt

if __name__ == '__main__':
  arguments = docopt(__doc__, version='Naval Fate 2.0')
  print(arguments)

from docopt import docopt
docopt(doc, argv=None, help=True, version=None, options_first=False)


```

```sh
pip install docopt==0.6.2
naval_fate.py ship Guardian move 100 150 --speed=15
```

```
```


