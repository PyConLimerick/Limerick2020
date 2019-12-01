## Understanding multithreading by deciphering the Cpython Intepreter source code	

* Area: General Python or Python based Frameworks.
* Level: Intermediate	A detailed look at a niche area of Python.	
* Requirements: Laptop and a microphone will suffice.


#### Abstract
"In the modern era of hybrid cores and processors, there is an in demand need for concurrent and parallel programming paradigms. 
Python, since its inception has amazing support for single threaded applications. 
The extensive use of Python in booming fields like Machine Learning has paved the way to constantly improve multi-threaded applications in Python.


I will speak from ground level covering very crucial aspects of Threading and Locks which will provide a better roadmap for community to develop better Python applications.

*  Program outcomes:
    -  How threading can improve performance, its pros and cons.
    -  What works best in which environment between threads and processes.
    -  Why GIL matters the most in Python
    -  How to leverage the power of open source source code to understand the crux of language.

*  Contents to be covered:

1. Threading for noobs:

    -  Terminologies: Process, threads, multithreading, multiprocessing, types of threads, locks, mutex, CPU and I/O bound processes.
    -  Multithreading in Python: Threading module (with example)
    -  Comparative analysis of Sequential vs Multithreaded execution in Python (with example)

2. Understanding the global interpreter lock (GIL):

    -  What and why of GIL
    -  Impact of GIL on CPU and I/O Bound Processes
    -  In-depth understanding of GIL using cpython interpreter source code
    -  Reference counting
    -  Ticks via context switching

3. Infamous concepts:

    -  Cooperative vs Preemptive multitasking
    -  Parallelism vs Concurrency
    -  Thread Safety in Python

4. Removing the GIL:

    -  Famous GIL removal patch
    -  Guido on GIL, Larry Hastings Gilectomy

5. Questions"	

