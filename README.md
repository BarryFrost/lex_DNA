## Simple Pratice about lex and yacc 

## Prerequisites
Download packages: bison, flex
```
sudo apt-get install bison flex -y
```
Compile lex file into c lang file
```
lex lex.l # output file: lex.yy.c
```
Compile lex.yy.c file to executable
```
g++ lex.yy.c # output a.out or specify the executable name with -o
```
feed the file.txt as input of a.out
```
./a.out file.txt
# output
Counter :
A: 15
T: 3
C: 11
G: 3
```
