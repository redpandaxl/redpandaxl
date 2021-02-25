## Wednesday, February 24, 2021, 10:14:14PM PST <1614233654>
Learning more about the data structurs class on udemy i was able to find
out more about how references and pointers work and why they are used. 

it was suggested by rwxrob to learn data structures from the point of
view of the C language, which is has been a good bridge between what
i have learned about OOP and statically typed golang. 

Making a note here to remember 2-3 ideas. 

```
1. Refrernce - A reference variable is an alias, that is, another name
   for an already existing variable. A reference, like a pointer, is
   also implemented by storing the address of an object. 
   A reference can be thought of as a constant pointer (not to be
   confused with a pointer to a constant value!) with automatic
   indirection, i.e the compiler will apply the * operator for you. 

2. Pointers - A pointer is a variable that holds memory address of
   another variable. A pointer needs to be dereferenced with * operator
   to access the memory location it points to. 

3. Stack vs Heap - using malloc to get into heap and heap can only be
   accessed through pointers. need to verify this understanding later

```
