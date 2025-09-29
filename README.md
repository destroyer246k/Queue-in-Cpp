# Queue-in-Cpp  

**Aim:** To study the concept of **Queue** in C++ and implement enqueue, dequeue, and display operations.  

**Tools:** GNU g++ compiler for local compilation or any online C++ compiler.  

# Theory  
A **Queue** is a linear data structure that follows the **FIFO (First In First Out)** principle.  
- **Enqueue:** Insert an element at the rear (back).  
- **Dequeue:** Remove an element from the front.  
- **Display:** Show all elements in the queue.  

Queues are useful in scheduling, buffering, printer management, and many real-world scenarios.  

### Types of Queues  
- **Simple Queue** – basic FIFO structure.  
- **Circular Queue** – last position connects to the first.  
- **Priority Queue** – elements are dequeued based on priority.  
- **Double-Ended Queue (Deque)** – insertion and deletion at both ends.  
# Synatx
```cpp
```
# **Program: Queue using Array**  

### Logic:  
A `Queue` class is implemented with `enqueue()`, `dequeue()`, and `display()` functions. `front` and `back` indices track the first and last elements.Overflow occurs when the queue is full.  Underflow occurs when the queue is empty.  

### Algorithm:  
1. Start  
2. Define `Queue` class with array, front, and back.  
3. For enqueue:  
   - If full, display overflow message.  
   - Else insert element and update `back`.  
4. For dequeue:  
   - If empty, display underflow message.  
   - Else remove element and update `front`.  
5. For display:  
   - If empty, show message.  
   - Else print all elements.  
6. In `main()`, perform enqueue, dequeue, and display.  
7. End  



# **Conclusion**  
Queues are important linear data structures that manage data in a **FIFO** manner. The array-based implementation demonstrates enqueue, dequeue, and display operations while handling overflow and underflow conditions. This makes queues useful in resource scheduling, buffering, and real-time applications.  
