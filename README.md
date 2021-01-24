# SHELL DATA PROCESSING


## CURL COMMAND
The command **curl "https://www.history.com/topics/folklore/bermuda-triangle" -O "data.txt"** is used to return the page text from a url and copies the output to a file.

## GIT BASH COMMANDS 
### TO PROCESS TEXT DATA
- tr ' ' '\12' < data.txt
Transform each space ' ' in the file into a return character '\12'

- tr ' ' '\12' < data.txt | sort
Sorts the output

- tr ' ' '\12' < data.txt | sort | uniq -c
Displays the count of the sorted output using uniq -c 

- tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr
Displays the sorted output in the numeric reverse order with -nr flag

- tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt
Move the content to a output file named result.txt

### MOST USED & IMPORTANT COMMANDS
- Up arrow in bash helps one to search through the history i.e. to access the previously used commands
In bash shell
- **-n** flag is used for **numeric-sort**.It compare according to string numerical value
- **-r** flag is used for **reverse** . It reverses the result of comparisons.
- One dash **-** is used with a single letter flag
- Two dashes **--** are used with more than one letter flag
- command **>** is used for Bash redirect
- command **>>** is used for Bash redirect & append 
- **ls** command helps to list the contents of the default directory
- **cat** command to displays the contents of text file
