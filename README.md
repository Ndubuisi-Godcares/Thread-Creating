# Thread-Creating

This code package includes two Java classes, MyThread and ThreadDemo, which demonstrate the creation and management of threads in Java.

MyThread Class
The MyThread class extends the Thread class and overrides the run() method. It takes a String parameter in the constructor to set the name of the thread. When the run() method is called, the thread enters a loop where it prints a start message, loops until it is interrupted, and then prints an end message. If the thread is interrupted during the loop, it prints an interrupt message before exiting the loop.

ThreadDemo Class
The ThreadDemo class creates two instances of MyThread, starts them, sleeps for 3 seconds, interrupts them, waits for them to finish, and then prints a final message.

To run the demo, simply execute the ThreadDemo class. It will output the messages from the MyThread instances as they run and then print the final message after the threads are finished.
