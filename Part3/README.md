# Reasons for concurrency and parallelism


To complete this exercise you will have to use git. Create one or several commits that adds answers to the following questions and push it to your groups repository to complete the task.

When answering the questions, remember to use all the resources at your disposal. Asking the internet isn't a form of "cheating", it's a way of learning.

 ### What is concurrency? What is parallelism? What's the difference?
 > *Concurrency is when several computations are executed i the same overlapping time period, they can be computed out of order without changing the result. 
Parallelism is when different threads/processes are running on the same or different data at the same time on multiple processors. These threads may communicate for instance about shared resources. 
The difference is that in parallell the task are completed at the same time. Because it uses different cores/processors *
 
 ### Why have machines become increasingly multicore in the past decade?
 > *The improvements in clock speed of processors has slowed. So to keep improving the processing speed of computers, we have instead moved to have multiple cores on our chips so we can run multipli processes at the same time.*
 
 ### What kinds of problems motivates the need for concurrent execution?
 (Or phrased differently: What problems do concurrency help in solving?)
 > *Your answer here*
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > *Your answer here*
 
 ### What are the differences between processes, threads, green threads, and coroutines?
 > *Your answer here*
 
 ### Which one of these do `pthread_create()` (C/POSIX), `threading.Thread()` (Python), `go` (Go) create?
 > *Your answer here*
 
 ### How does pythons Global Interpreter Lock (GIL) influence the way a python Thread behaves?
 > *Your answer here*
 
 ### With this in mind: What is the workaround for the GIL (Hint: it's another module)?
 > *Your answer here*
 
 ### What does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*
