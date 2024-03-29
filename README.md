# Linux-Kernel-Modules
How to create a kernel module and load it into Linux kernel?

Almost all the modern operating-system's designs involve using loadable Kernel modules. Here, the kernel has a set of core components and links in additional services via modules. This linking can be done either at boot time or during run time. Linking services dynamically is preferable to adding new features directly to the kernel, which would require the recompiling the kernel every time a change was made.

For eg. We might build CPU scheduling and memory management algorithms directly into the kernel and then add support for different file systems by way of loadable modules.

The advantage of developing kernel modules is that it is a relatively easy method of interacting with the kernel. It allows you to write programs that directly invoke 
kernel functions. This is all kernel code that directly interacts with the kernel.
