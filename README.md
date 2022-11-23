## PROJECT MONTY - 0x19. C - Stacks, Queues - LIFO, FIFO


## DEFINTIONS:

## Enqueue & Dequeue:
FIFO - Stands for First in, First out, and it is a method that is for handling data structures where the first element is processed first and the newest element is processed last.The data structure that implements FIFO is a queue. This works like a line. You decide to go to the movies. There is a long line to buy tickets, you decide to get into the queue to buy tickets, that is "Enqueue". at some point you are at the front of the line, and you get to buy a ticket, at which point you leave the line, that is "Dequeue".

![1582608897-71449](https://user-images.githubusercontent.com/108279441/202910424-f785f48f-2a4b-477e-a1b4-55d807319f14.png)


## Stacking:
LIFO - Stands for Last in, First out it is the same as First in, Last out (FILO). It is a method that is for handling data structures where the last element is processed first and the first element is processed last.The data structure that implements LIFO is a stack. Imagine a stack of paper. The last piece put into the stack is on the top, so it is the first one to come out. This is LIFO. Adding a piece of paper is called "pushing", and removing a piece of paper is called "popping".

![1*r4Bfo3rrFprzFM2zbgzZXA](https://user-images.githubusercontent.com/108279441/202910416-0f9a1d0f-c85d-43cf-a38c-be35e39dc93e.jpeg)

## EXTRA INFO:
Project file: monty file

➡where file is the path to the file containing Monty byte code

➡If the user does not give any file or more than one argument to your program, print the error message USAGE: monty file, followed by a new line, and exit with the status EXIT_FAILURE

➡If, for any reason, it’s not possible to open the file, print the error message Error: Can't open file <file>, followed by a new line, and exit with the status EXIT_FAILURE
  
➡where <file> is the name of the file
  
➡If the file contains an invalid instruction, print the error message L<line_number>: unknown instruction <opcode>, followed by a new line, and exit with the status EXIT_FAILURE
  
➡where is the line number where the instruction appears.
  
➡Line numbers always start at 1
  
➡The monty program runs the bytecodes line by line and stop if either:
  
➡it executed properly every line of the file

➡it finds an error in the file
  
➡an error occured
  
➡If you can’t malloc anymore, print the error message Error: malloc failed, followed by a new line, and exit with status EXIT_FAILURE.
  
➡You have to use malloc and free and are not allowed to use any other function from man malloc (realloc, calloc, …)


## COLLABORATORS:
@Frandy4ever - (Frandy Slueue)

@MicoBledsoe - (Mico Bledsoe)
