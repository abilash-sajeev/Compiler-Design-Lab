## Program to Convert the BNF rules into YACC form and write code to generate abstract syntax tree. ##

1. Compile the lex program using the command   
    `lex ast.l`  
2. Compile the yacc program using the command  
    `yacc -d -v ast.y`  
3. Now compile and run the lex.yy.c and y.tab.c files generated using the command  
    `gcc lex.yy.c y.tab.c -lm -w`  
4. Execute the program by providing an input file  
    `./a.out input.txt`
