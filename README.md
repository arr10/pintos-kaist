Brand new pintos for Operating Systems and Lab (CS330), KAIST, by Youngjin Kwon.

The manual is available at https://casys-kaist.github.io/pintos-kaist/.

TIMER TODO:
- Create a global list in timer.c file, using list.c implementation. 
- Block a thread in timer.c file, timer_sleep function
- Add a following tuple: (PCB, time_left) to the list
- In timer_interrupt in timer.c file, check the list and time_left--, and if time_left == 0, unblock the thread.
