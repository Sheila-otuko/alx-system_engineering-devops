 1. alias ls='rm *'-Create a script that creates an alias.Name: ls Value: rm *
 2. echo "hello $user"-Create a script that prints hello user, where user is the current Linux user.
 3. PATH=$PATH:/action-Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
 4. echo $PATH | tr "." "\n" | wc -l
 5. env-lists global variables
 6. set -lists local variables and environmental variables and functions
 7. BEST="School"
 8. export BEST="School"
 9. echo $((128+TRUEKNOWLEDGE))-prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE10. echo $((POWER/DIVIDE))-Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
11. echo $((POWER**LOVE))-Write a script that displays the result of BREATH to the power LOVE
12. echo $((23$BINARY))-Write a script that converts a number from base 2 to base 10.
13. echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"-Create a script that prints all possible combinations of two letters, except oo.
14. printf '%.2f\n' $NUM-Write a script that prints a number with two decimal places, followed by a new line. 
