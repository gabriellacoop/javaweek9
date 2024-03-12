# javaweek9

1.Post-Lab Questions:


1. How does thread creation differ when using `Thread` vs. `Runnable`?

Thread provides a straightforward mechanism for creating and managing threads, it comes with limitations due to Java's single inheritance constraint. On the other hand, Runnable promotes better object-oriented design, reusability, and resource sharing, making it a preferred choice in many scenarios.

2. Describe the lifecycle of a thread in your own words.

For me It means varoius stages that goes during the execution of the code, example : New, Runnable, Running, Blocked/Waiting, Timed, and Terminated.


3. What did you observe about the order of execution of threads in Exercise 4?

Is organized by the time that is printed.

4. What happens when a thread is interrupted?

it will throw InterruptedException

