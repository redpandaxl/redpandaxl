## Friday, March 12, 2021, 6:47:32PM PST <1615603652>


Linked Lists - why we need dynamic structured linked list

1. Problem with Arrays
2. difference b/w array and linkedlist 

```
int A[100] - during runtime we can not dynamically allocate size of the
array. 
```

Making a node is part of the linked list. 
In this case:
2 value array, first element of node is a pointer from stack to heap
with a value. The second index(?) of the node is either null or
a pointer to another node and the pattern continues until there is
a node with a null value. 

This linked list would allow a way to dynamically add to the size of
a needed array. 

Linked list is always found in the heap. 

Defintion of a linked list - collection of nodes that each node contains
data and pointer to another node. 

to define a node you have to define 2 things. 

1. data
  data can be any data type, float int char etc. 
2. pointer
  pointer is a pointer of its own type. 

Node structure
Data | next

Clang structure
struct Node
{
  int data; // int takes 2 bytes
  struct Node *next; // struct takes 2 bytes
};
Self referencial structure - used in linked list. 

Code Example

struct Node *p;
p=(struct Node *)malloc(sizeof(struct Node));

p=new Node; //c++ version of creating struct into heap. 

p->data
p->next

More Examples
struct Node *p, *q;
q=p;
P and Q point to same address. 
q = p->next
Q is pointing on next node of P.

p=p->next
p moves from address 200 to 210 instead. it has moved p to the next
node. Useful statement in linked lists. 
