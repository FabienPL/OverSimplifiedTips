
Heap/Stack

Both are stored in RAM.
Stack: memory set aside for a thread. each thread has its own stack. 
    A block is created when a function is called, and deleted when the function returns. LIFO
    Too many function recursion -> Stack Overflow!
    Size set when created.
    Stores return function addresses, local variables.
Heap: memory set aside for dynamic allocation. Shared by all the threads.
    No rules -> more complex to keep track, slower
    No size set, can grow.
    Stores any new object
Memory leak: resource taking up memory but not used anymore.
