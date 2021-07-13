This repository contains code for custom memory manager. 

  In C++ new/malloc are memory allocators and delete/free are deallocators. When new/malloc requests memory to operating system, OS shifts from
user mode to kernel mode. It requires time for making this shifts. So we have designed memory manager which will decrease
number of shifts, which will increase performance of application.
