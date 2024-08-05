### Problem
read the names in new line, store in an array.
print the entire array.

### Solution
```sh
#!/bin/bash

names=()

while IFS= read -r name
do
    names+=($name)
done
echo ${names[@]}

```