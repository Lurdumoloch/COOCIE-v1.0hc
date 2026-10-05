# COOCIE-v1.0hc
A small and basic Programming Language with its own IDE. It has a grafical and a terminal output and was coded in Turbowarp(faster scratch). It has basic function like if else, variables , render a few forms AND more.

## How it works:
Hmm good question i guess, let me try to explain.
So it works while runtime and uses the line and trys to find keywords in it. If it finds a Keyword or Keychar it starts to do the command thats cnnected to the keyword... 
The if stuff works like this : 
- there is one var named "in if" this variable is at standard deep 0, if the code gets now to the if and the condition is true it sets "in if" to current deep +1.
- Before a line gets checked for keyword we check if "in if" is bigger then 0, if it is then we check if current deep is smaller then the "in if " var if yes then we set it to zero.

## SYNTAX and COMMANDS
### Variables
Variables are important so they got the **$** char
*$x=20* creates a variable x and gives it value 20
*$x$* is used to get the value stored in var x
### Print()
Print is a command to write smth in the Terminal. 
*Print(hello)* adds hello to terminal
*Print(45)* adds 45 to the terminal
### wait()
yeah it just waits the amout of seconds u put in there
*wait(2)* waits to seconds👀
<img width="548" height="538" alt="20261003-2024-25 8352933" src="https://github.com/user-attachments/assets/ce508c26-64e3-4c3e-8712-a7a556d07eb5" />
### repeat(x):
Repeat is a loop repeating  nxt lines of code that are > in. It repeats it x times.
*repeat(3):*
*>print(hello)*
prints 3 times hello

## Bibs
### Turtle
<img width="1223" height="936" alt="image" src="https://github.com/user-attachments/assets/f7b3f53c-9285-44d0-98a3-07b7276b42ee" />
small demo (=
Turtle is another tool for grafic output.
#### Commands 
they all need to start with "turtle."
##### move(n)
moves the turtle in current direction by n steps
#### turn()
turns the turtle in ↩️ with the given degree.
#### dir()
Sets the turtle die to a given value
#### pos(X;Y)
turtle jumps to the given position.
#### up
pen up
#### down
pen down (it is that easy lol)


## BUGS and how they got more or less fixed
This is not a complete list!!!
### 1)<img width="1245" height="937" alt="image" src="https://github.com/user-attachments/assets/27904289-58ec-4818-99a8-710fcd655512" />
The bug is the - number) in code part it is llinked to the scrollweel, changed formula now it works.(v0.1.4)
