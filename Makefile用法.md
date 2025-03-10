
**目标 : 依赖1 依赖2 ...**  
**[TAB]命令**  
**当“依赖”比“目标”新，执行它们下面的命令。我们要把上面三个命令写成makefile规则，如下：**  
test ：a.o b.o          //test是目标，它依赖于a.o b.o文件，一旦a.o或者b.o比test新的时候，  
就需要执行下面的命令，重新生成test可执行程序。  
gcc -o test a.o b.o  
a.o : a.c              //a.o依赖于a.c，当a.c更加新的话，执行下面的命令来生成a.o  
gcc -c -o a.o a.c  
b.o : b.c            //b.o依赖于b.c,当b.c更加新的话，执行下面的命令，来生成b.o  
gcc -c -o b.o b.c  
