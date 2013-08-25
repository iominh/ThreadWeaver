This is a fork of the [Thread Weaver project](https://code.google.com/p/thread-weaver),
version 0.20. It was updated to use Maven instead of Ant.

[Alasdair Mackintosh](https://code.google.com/u/alasdair.mackintosh/) is the original author.

# Description

Thread Weaver is a framework for writing multi-threaded unit tests in Java.

It provides mechanisms for creating breakpoints within your code, and for halting execution of a thread when a breakpoint is reached. Other threads can then run while the first thread is blocked. This allows you to write repeatable tests for that can check for race conditions and thread safety.

# Install

After installing Maven, run "mvn clean install" in the root directory
to build the framework and run the unit tests.

