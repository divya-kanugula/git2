# git2
A code for this
#!/bin/bash

echo "Enter a number:"
read num

if [ "$num" -eq 0 ]; then
    echo "Reciprocal of 0 is not defined."
else
    reciprocal=$(awk "BEGIN {print 1/$num}")
    echo "Reciprocal of $num = $reciprocal"
fi
