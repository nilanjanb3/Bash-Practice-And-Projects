### Problem
Given 2 numbers, read it as stdin and print addition, substraction, multiplication and division in a new line as stdout.

### Solution
```sh
#!/bin/bash

read -r a
read -r b

echo $(expr $a + $b )
echo $(expr $a - $b )
echo $(expr $a \* $b ) # Note that * symbol needs to be escaped with a backslash (\) to prevent it from being interpreted as a wildcard character by shell.
echo $(expr $a / $b )
```