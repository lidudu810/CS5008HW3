# Homework 03 - Stacks and Queues -

Name: Chengyi Li

Github Account name: lidudu810

How many hours did it take you to complete this assignment (estimate)? 5hr

Did you collaborate with any other students/TAs/Professors? If so, tell us who and in what capacity.  
- one per row, add more if needed
Student: Zhanpeng Tong

Did you use any external resources (you do not have to cite in class material)? (Cite them below)  
- one row per resource
no

(Optional) What was your favorite part of the assignment? 

(Optional) How would you improve the assignment? 

## Further Thinking Questions

1. Circular queues are used quite a bit in operating systems and high performance systems, especially when performance matters. Do a little outside research, and answer this question specifically: Why is a ring buffer useful and/or when should it be used? 

A ring buffer, also known as a circular buffer, is a data structure that is useful in situations where data needs to be processed efficiently in a first-in, first-out (FIFO) order. It is essentially a fixed-size buffer that is treated as though it is connected end-to-end, forming a loop. When data is added to the buffer, it is written to the next available slot in the buffer, and when the buffer is full, new data overwrites the oldest data in the buffer.
The ring buffer is particularly useful in real-time systems or embedded systems where memory is limited and speed is critical. It allows data to be continuously processed without needing to allocate new memory or perform expensive memory operations, which can lead to increased performance and reduced overhead. Additionally, the circular buffer can be implemented using low-level operations, such as pointer manipulation, which can further improve performance.

2. We are going to talk about stacks quite a lot in this course, so it will be important to understand them. Do a little outside research, and edit this section of the readme answering specifically: Why is a stack useful and/or when should it be used?

A stack is a data structure that stores and retrieves data in a last-in, first-out (LIFO) order. It is commonly used in computer science and programming for a variety of purposes, such as function calls, expression evaluation, and memory management.
The stack is particularly useful in situations where a temporary storage space is needed for data that must be accessed in reverse order. For example, when a function is called, the arguments and return address are stored on the stack, and when the function returns, the values are popped off the stack in reverse order. This allows the program to keep track of the current function call and return to the previous function call once the current call is complete.

In addition to function calls, the stack is also used for other applications such as implementing recursive algorithms, parsing expressions, and storing local variables in a function. The simplicity and efficiency of the stack data structure make it a valuable tool for many programming tasks.

For each of these questions, we are expecting your answer to be in the range of 2-3 paragraphs (can include complexity, example usage, pros/cons, etc). Make sure to cite your sources. It is recommended you use [IEEE citation style](https://owl.purdue.edu/owl/research_and_citation/ieee_style/ieee_overview.htm) as it is most common for CS papers and research. 


## Important notes

* Your code **must compile and run** on the Khoury machines to earn credit. Make sure you test your programs on these machines, as this is where we grade your assignments.
* You must commit any additional files(if any) into your repository so we can test your code.
  * Points will be lost if you forget!
* Do not forget, once you have pushed your changes to your repo make sure that you **submit them to Gradescope before the assignment deadline!**

