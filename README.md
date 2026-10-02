# COOCIE-v1.0hc
A small and basic Programming Language with its own IDE. It has a grafical and a terminal output and was coded in Turbowarp(faster scratch). It has basic function like if else, variables , render a few forms AND more.

## How it works:
Hmm good question i guess, let me try to explain.
So it works while runtime and uses the line and trys to find keywords in it. If it finds a Keyword or Keychar it starts to do the command thats cnnected to the keyword... 
The if stuff works like this : 
- there is one var named "in if" this variable is at standard deep 0, if the code gets now to the if and the condition is true it sets "in if" to current deep +1.
- Before a line gets checked for keyword we check if "in if" is bigger then 0, if it is then we check if current deep is smaller then the "in if " var if yes then we set it to zero.

## SYNTAX and COMMANDS
### Print()
