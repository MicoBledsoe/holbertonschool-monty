# PROJECT MONTY - 0x19. C - Stacks, Queues - LIFO, FIFO

## Overview

This repository hosts the "Project Monty," an educational project designed to introduce students to the complexities of managing data structures such as stacks and queues through a custom Monty bytecode interpreter. This project is part of a comprehensive computer science curriculum that focuses on deeper understanding of data handling and manipulation.

## Definitions and Concepts

### FIFO - First In, First Out

FIFO refers to a queue management principle where the first element added to the queue is the first one to be removed. This concept is best visualized as a line at a movie theater:
- **Enqueue**: Joining the line to purchase a ticket.
- **Dequeue**: Reaching the front and purchasing the ticket, thereby leaving the queue.

![Queue Illustration](https://user-images.githubusercontent.com/108279441/202910424-f785f48f-2a4b-477e-a1b4-55d807319f14.png)

### LIFO - Last In, First Out

LIFO refers to a stack management principle where the last element added to the stack is the first one to be removed. Consider a stack of plates:
- **Pushing**: Placing a plate on top of the stack.
- **Popping**: Removing the top plate from the stack when needed.

![Stack Illustration](https://user-images.githubusercontent.com/108279441/202910416-0f9a1d0f-c85d-43cf-a38c-be35e39dc93e.jpeg)

## Project File Details

### Monty Bytecode Interpreter

The Monty interpreter reads Monty bytecode files which contain instructions for operating on stacks and queues. The interpreter processes these instructions line-by-line, manipulating data structures accordingly.

### Usage Instructions

To use the Monty interpreter:
#```bash
./monty [path_to_file]

path_to_file: The path to the Monty bytecode file to be executed.


### Part 4: Error Handling
```markdown
### Error Handling

The interpreter robustly handles errors, including:
- **File errors**: If no file is given, multiple arguments are provided, or the file cannot be opened.
- **Syntax errors**: If an invalid instruction is encountered or if there are issues with the line format in the bytecode file. Specific errors will provide detailed messages to assist in debugging.
- **Memory errors**: Proper messages and exits if the system cannot allocate memory.

## Collaborators
- **Frandy Slueue** (@Frandy4ever)
- **Mico Bledsoe** (@MicoBledsoe)
