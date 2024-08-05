### Problem
Read 3 sides of a triangle and print if it is EQUILATERAL or ISOSCELES or SCALENE.


### Solution

```sh
#!/bin/bash

read -r x
read -r y
read -r z


if [[ $x -eq $y ]] && [[ $y -eq $z ]]
then
    echo "EQUILATERAL"
elif [[ $x -eq $y ]] || [[ $y -eq $z ]] || [[ $x -eq $z ]]
then
    echo "ISOSCELES"
else
    echo "SCALENE"
fi
```
