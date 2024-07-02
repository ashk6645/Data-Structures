# Data types in Java
                                                   Data Types-(Java)              
                                                        |
                                             ---------------------------
                                             |                         |
                                      Primitive                     Non-Primitive
                                         |                                |                                
                                  -----------------                  ----------------------
                                  |               |                  |      |      |     |
                                Boolean          Numeric           String  Array  Class  etc
                                  |               |
                            boolean(1 bit)    -----------------------------------------
                                              |     |     |      |      |      |      |    
                                            char  byte   short   int   long   float  double

[1 byte = 8 bit]
char   = 2 byte
byte   = 8 bit
short  = 2 byte
int    = 4 byte
long   = 8 byte
float  = 4 byte
double = 8 byte

Example:  String name = "Ashu"; ( 4 * 2 = 8 byte)



Variable: Variable is the name of memory location that can store data.
int a = 10;   (a is the variable)
a = a+10;
a = 20;

Types of Variable

i)   Local variable:    Declared inside a block or function.
                        Accessed inside the same block or methode.
                        Stored in the form of Stack memory.
                        When methode, block get executed, variables are allocated.
                        Can't be used with local variables.

ii)  Instance variable: Declared inside the class but outside the methode, constructor.
                        It can be accessed inside all the blocks, methodes which are present in the class.
                        Stored in Heap memory.
                        Variable get memory allocated when object is created.
                        Access specifier can't be used.

iii) Static variable:   Decalred within a class using static keyword but not inside methode, cosntructor.
                        Scope is same as instance variable.
                        Stored in non-heap memory or static memory.
                        Variable gets memory allocated when we run the program and .class file is loaded
                        Access modifiers can't be used.




  

