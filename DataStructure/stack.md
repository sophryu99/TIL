# Stack

Stack is a linear data structure based on the `Last in First Out (LIFO)` principle.

## Main methods

- empty() – Returns whether the stack is empty
- size() – Returns the size of the stack
- top() / peek() – Returns a reference to the topmost element of the stack
- push(a) – Inserts the element at the top of the stack
- pop() – Deletes the topmost element of the stack

### Time Complexity
|empty()|size()|top()|push()|pop()|
|------|-----|-----|-----|-----|
|O(1)|O(1)|O(1)|O(1)|O(1)|

## Advantages

- simple implementation
- efficient for adding and removing elements
- In order to reverse the order of elements we use the stack data structure.
- Stacks can be used to implement undo/redo functions in applications.


## Drawbacks
- Restriction of size:  if they are full, you cannot add any more elements to the stack
- do not provide fast access to elements other than the top element.
- do not support efficient searching
