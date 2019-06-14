# VecLib
Implementing a Vector Library in C

# Functions Implemented

1. init()
Construct vector.
Prototype: vector_int *vec_init(int size, int *status);

2. destroy()
Vector destructor.
Prototype: void destroy(vector_int *v, int *status);

3. assign()
Assign vector content.
Protoype: int *assign(int position, int value, vector_int *v, int *status);

4. size()
Return number of elements.
Prototype: int size(vector_int *v, int *status);

 5. capacity()
Return size of allocated storage capacity.
Protoype: int capacity(vector_int *v, int *status);

6. empty()
Test whether vector is empty.
Protoype: int empty(vector_int *v, int *status);

 7. at()
Access element.
Prototype: int *at(int position, vector_int *v, int *status);

8. front()
Access first element.
Prototype: int front(vector_int *v, int *status);

9. begin()
Return iterator to beginning.
Prototype: int *begin(vector_int *v, int *status);

10. back()
Access last element.
Prototype: int back(vector_int *v, int *status);

11. end()
Return iterator to end.
Prototype: int *end*(vector_int *v, int *status);

12. push_back()
Add element at the end.
Protoype: int *push_back(int element, vector_int *v, int *status);

13. pop_back()
Delete last element.
Protoype: int pop_back(vector_int *v, int *status);

14. insert()
Insert an element.
Prototype: int *insert(int position, int value, vector_int *v, int *status);

15. erase()


16. swap()
Exchange values of two elements.
Prototype: void swap(int i, int j, vector_int *v, int *status);

17. clear()
Clear content.
Prototype: void clear(vector_int *v, int *status);

18. sort()


