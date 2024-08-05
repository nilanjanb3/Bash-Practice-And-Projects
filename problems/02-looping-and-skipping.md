### Problem
Print 1 to 99 with a 2 step gap.
1 
3
5
.
.
.
99

### Solution
```sh
#!/bin/bash

for (( i=1 ; i<100 ; i=i+2)) {
    echo $i
}
```