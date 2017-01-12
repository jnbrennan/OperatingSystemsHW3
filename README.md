# OperatingSystemsHW3
Locks and Threads

Requirements per professor:

The starter program is buggy and performs very poorly. It is your job to make it work and work well. The two main problems you will fix are:
-None of the shared data structures have locks. You will need to identify critical sections and place the appropriate locks
-The way data is read into the program is very inefficient. It is reading in line by line and passing to the computation threads the numbers. Because the computation threads are a lot faster, everything is waiting on I/O. Because I/O blocks a lot, the CPUs aren't kept busy.
 
To get full points on this assignment you will need to modify the program so that:
-It prints out the correct output consistently without crashing
-When your program should be able to take advantage of at least two processor cores and keep them busy 75% of the time.
Your code should be readable.
 
To get extra credit (ACHIEVED):
I will be doing homework #3 also. If your program is faster than mine or comes within 25% of the performance I get, You will get 10% extra credit. Extra credit is not awarded if your program crashes or produces inconsistent results.
