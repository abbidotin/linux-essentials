# Linux Architecture
Linux architecture describes how the different components of a Linux system work together.

---

## Main Components
A Linux system can be viewed as several layers:
```text
+----------------------+
|     Applications     |
+----------------------+
           ↓
+----------------------+
|        Shell         |
+----------------------+
           ↓
+----------------------+
|       Kernel         |
+----------------------+
           ↓
+----------------------+
|       Hardware       |
+----------------------+
```

---

## Hardware
The hardware is the physical part of the computer.
Examples include:
* CPU
* RAM
* Storage
* Network devices
* Input and output devices

The kernel manages access to these hardware resources.

---

## Kernel
The **kernel** is the core of the Linux operating system.
It manages:
* CPU and processes
* Memory
* Hardware devices
* Filesystems
* Networking

The kernel provides an interface between applications and hardware.

---

## Shell
The **shell** provides an interface for users to interact with Linux.
It accepts commands and communicates with the kernel to perform operations.
Example:
```bash id="3m8j7n"
ls
```

The shell interprets the command and requests the required operation from the system.

---

## Applications
Applications are programs that perform specific tasks for users.
Examples include:
* Web browsers
* Text editors
* Development tools
* System utilities
* Cloud management tools

Applications use the services provided by the operating system rather than directly controlling the hardware.

---

## System Utilities
System utilities are programs that help users and administrators manage the Linux system.
Examples include tools for:
* File management
* User management
* Process management
* Networking
* System configuration

---

## How the Components Work Together
When I run a command or application:
```text id="n9d2jo"
User
 ↓
Application / Shell
 ↓
System Call
 ↓
Kernel
 ↓
Hardware
```

The kernel processes the request and manages the required hardware resources.

---

## Key Takeaways
* Linux architecture consists of multiple layers that work together.
* The kernel is the core component responsible for managing system resources.
* The shell provides a command-line interface.
* Applications use operating-system services to perform tasks.
* The kernel provides the connection between software and hardware.

---

## References
* Cisco Networking Academy — Linux Essentials
