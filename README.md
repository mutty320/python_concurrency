# Python Concurrency

Welcome to Python Concurrency!

## Introduction

Explore Python concurrency in two approaches:

1. **Multithreading**: Ideal for I/O-bound tasks, enabling concurrent execution.

2. **Multiprocessing**: Best for CPU-bound tasks, enables true parallelism.

Both approaches utilize synchronization tools to prevent race conditions. 
In this project, I've implemented Locks and Semaphores for multithreading, 
and state sharing for multiprocessing.

I've also explored asynchronous programming to eliminate GIL-related issues.

## Project Overview
Combine I/O and CPU tasks to showcase different concurrency techniques and their benefits.

- The I/O task is downloading images from a list of URLs.
- The CPU task is to resize the images.

- v1: Initial program structure.
- v2: Multithreading enhances download speed.
- v3: Introduce synchronization tools (e.g., Locks, Semaphores).
- v4: Demonstrate semaphore usage for controlled downloads.
- v5: Multiprocessing for image resizing, improved performance.
- v6: Multithreading for downloads, multiprocessing for resizing.
- v7: Utilize IPC and manual process management with multiprocessing queues.

## Version History

Documented with Git tags, offering an organized history of project evolution.

## Project Repository

Explore the project on [GitHub](https://github.com/mutty320/python_concurrency). Fork, clone, or contribute!

## Tags

#Python #Concurrency #MultiThreading #Multiprocessing #AsyncProgramming
