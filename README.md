# RTOS <br>

In this example, we are using the Arduino FreeRTOS library to create two tasks (task1 and task2) with different priorities. The higher priority task (task1) will be executed first, followed by the lower priority task (task2). The scheduler manages the execution of tasks based on their priority, and provides built-in mechanisms for task synchronization, such as semaphores, mutexes, and message queues. Note that in an RTOS application, the loop() function is not used, as the scheduler manages the execution of tasks.
