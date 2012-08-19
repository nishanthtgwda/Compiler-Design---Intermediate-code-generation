INTERMEDIATE CODE GENERATION FOR IF ELSE CONSTRUCT

The main objective of the project is to generate the intermediate code for the given IF-ELSE Statement. It consists of four main sections , the conditional section inside the IF statement , the THEN part of the statement which the code enters if the given IF condition is true , the ELSE part of the statement which the code enters if the given IF condition is false , and the statements after the ELSE construct which is evaluated after either the IF or ELSE part.

Commands to be followed 

lex intif.l
yacc -d intif1.y
cc y.tab.c -ll -ly
./a.out

All the codes and text used here are the copyright of the developers mentioned. Any unauthorized usage without prior notice shall be liable to prosecution *All Rights Reserved*


