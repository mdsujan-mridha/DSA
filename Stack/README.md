<h1 align="center">Stack using C++</h1>

A stack is a linear data structure that follows a particular order for operations. The order is Last In, First Out (LIFO), meaning the last element added to the stack is the first one to be removed. Think of it like a stack of plates; you add plates to the top, and you also remove plates from the top.

## Key Operations

- **push()**: When we insert an element in a stack then the operation is known as a push. If the stack is full then the overflow condition occurs.
- **pop()**: When we delete an element from the stack, the operation is known as a pop. If the stack is empty means that no element exists in the stack, this state is known as an underflow state.
- **isEmpty()**: It determines whether the stack is empty or not.
- **isFull()**: It determines whether the stack is full or not.
- **peek()**: It returns the element at the given position.
- **count()**: It returns the total number of elements available in a stack.
- **change()**: It changes the element at the given position.
- **display()**: It prints all the elements available in the stack.

## PUSH operation

The steps involved in the PUSH operation are given below:

- Before inserting an element in a stack, we check whether the stack is full.
- If we try to insert the element in a stack, and the stack is full, then the overflow condition occurs.
- When we initialize a stack, we set the value of top as -1 to check that the stack is empty.
- When the new element is pushed in a stack, first, the value of the top gets incremented, i.e., top = top + 1, and the element will be placed at the new position of the top.
- The elements will be inserted until we reach the max size of the stack.

![Alt text](https://static.javatpoint.com/ds/images/ds-stack2.png)


## POP operation

-  Before deleting the element from the stack, we check whether the stack is empty.
-  If we try to delete the element from the empty stack, then the underflow condition occurs.
-  If the stack is not empty, we first access the element which is pointed by the top 
-  Once the pop operation is performed, the top is decremented by 1, i.e., top=top-1.

![Alt text](https://miro.medium.com/v2/resize:fit:720/format:webp/0*XBQwQqNoaSFNZVGw.png)
