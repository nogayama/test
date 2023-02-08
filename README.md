# test

<table><tr><td> Shellscript </td> <td> Python </td></tr><tr>
<td>

```bash
#!/usr/bin/env sh

cat abc.txt | grep a > a.txt
```

</td><td>

```py
#!/usr/bin/env python3
from dw import *

cat("abc.txt") | grep("a") > "a.txt"
```

</td></tr></table>


# b

<table><tr><td> Shellscript </td> <td> Python </td></tr><tr>
<td>

```bash
$ cat abc.txt | grep a
a
```

</td><td>

```py
>>> cat("abc.txt") | grep("a")
a
```

</td></tr></table>
