### Problem
Print numbers from 1 to 50
1 2 3 4 5 ... 50


### Solution
```sh
#!/bin/bash

for (( i=1 ; i<=50 ; i=i+1 ))
do
    echo $i
done
```