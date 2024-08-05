### Problem
read an input
</br>
if input is y or Y --> Output YES
</br>
else if input is n or N --> Output NO


### Solution
```sh
#!/bin/bash


read -r ch

if [[ $ch == 'y' ]] || [[ $ch == 'Y' ]]
then
    echo "YES"
else
    echo "NO"
fi
```