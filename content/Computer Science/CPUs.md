---
title: "CPUs: The Brains of Computers."
---
*-By Abdulrahman Osman*

The CPU(Central Processing Unite) is the main component in any computer. It serves as the brain of the machine, computing and executing instructions to make the computer actually *work*.
In this article I will go over some of the common terms used in CPUs and explain them briefly.
## Cores & Threads:
These are terms that we hear a lot when watching benchmarks of a processor or when we look for a new laptop or PC to buy, but what do they actually mean ?

A Core is a single processing unit within the CPU that can execute instructions.
Having multiple cores within a CPU can allow the CPU to execute different processes simultaneously-since each core is a processor in itself, this is what makes modern computers capable of running a bunch of different tasks all at once.

What is a Thread then ? A thread is a sequence of instructions within a program. In a processor, it refers to the number of independent instructions sequences a CPU core can handle at the same time.
This definition might give rise to the misconception that when a CPU supports hyperthreading, it executes multiple sequences of instructions (Threads) **simultaneously**, which is not entirely correct.
When a processor is executing a sequence of instructions, at some points some of its resources stay on idle while other processes execute; a CPU that supports hyperthreading can take the second thread to execute it and utilize its idle parts to execute some of it.

More threads doesn't necessarily mean a better performance since hyperthreading is just a CPU core sharing its resources with two different threads.  

## Clock Speed:
Clock speed is a metric of the frequency at which the processor works. A clock cycle is timing signal the CPU uses to coordinate and synchronize its operations.
Clock Speed is how many clock cycles a processor completes in a single second; it's measured in Hertz(Hz). 
`1 Hertz = 1 Clock Cycle per second`

Modern computers reach the Gigahertz scale (1,000,000,000 Hz). The computer I am using right now to write this article has the clock speed of 3.5GHz which means that it completes 3.5 billion clock cycles in a second.

## Logical Processors:
Logical processors are basically the amount of processors (cores) the operating system can see.
The amount of logical processors is the product of the amount of physical cores with the number of threads each core can handle.

---

### References:
[link1](https://www.cgdirector.com/cpu-cores-vs-logical-processors-threads/)


[[Computer Science |parent node]]