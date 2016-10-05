These are used to translate high level languages into machine code.

A **compiler** reads the whole high-level code (the source code) and, if there are no errors, translates it into a complete machine code program (the object code) which is output as a new file and can be saved.

### Advantages of using a compiler

- The translation is done once only and as a separate process.
- The program that is run is already translated into machine code so is much faster to execute.
- It protects the software from competitors who might otherwise be able to see how it is designed and built.

### Disadvantages of using a compiler

- If it encounters any errors, it carries on trying to compile the program and reports the errors at the end. The programmers then have to use the error messages to identify and remove the bugs.
- You cannot change the program without going back to the original source code, editing that and recompiling.

An **interpreter** reads the source code one instruction or line at a time, converts this line and executes it. The next line is read and translated and so on. This has to be done each time the program is run.

### Advantages of using an interpreter

- When an error is found, the interpreter reports it and stops so the programmer knows where the error has occurred.
- The program can be easily edited as it always exists as source code.

### Disadvantages of using an interpreter

- Every line has to be translated every time it is executed and therefore it is slower.

Have a look at this video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/1OukpDfsuXE" frameborder="0" allowfullscreen></iframe>
