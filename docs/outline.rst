working outline
===============

- Where your code runs - what a "process" is

  - Running code in a browser vs. running directly on an OS

- Operating system basics

  - Processes, file systems, memory, and networks
  - A little deeper on networks: DNS, IP addresses, ports &amp; sockets
  - IP v4 and IP v6, TCP &amp; UDP, DHCP, ZeroConf/Avahi
  - WTF is a 7 layer ISO model anyway, and why do I care?

- Physical &amp; virtual devices and IO

  - Serial ports, block and character devices, what is POSIX
  - USB and Bluetooth
  - Specialized hardware (GPUs, Accelerators, etc)

- Practicals for working with processes:

  - shell scripts and some of Unix CLI concepts
  - commands, pipes, STDOUT, STDERR, STDIN
  - environment variables, and shell tests

- Some basics about how operating systems work:

  - Init, systems, hierarchy of processes and how they coordinate
  - Kernel vs. user space and permissions, and privileges
  - Memory, Buffers, and the various dials that can be tuned (queue theory)
  - Sandboxing, background tasks, and scheduling

- Another layer of indirection:

  - Containers and VMs
  - Shared vs emulated resources
  - Cloud resources to IoT: you have a budget: CPU, Mem, IO
  - Smaller and smaller bits of computation: microprocessors and embedded
    devices

- Physical stuff breaks, all the time

  - Redundancy and consistency
  - Networks, latency, and information theory
  - Why and how these fundamentals expose constraints for development work
