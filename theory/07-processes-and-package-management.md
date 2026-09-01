## Linux Processes
A **process** is a running instance of a program. Linux manages processes and allocates system resources such as CPU time and memory to them.

### Process Identification
Each process has a unique **Process ID (PID)**. Processes can also have relationships with other processes, forming a parent-child hierarchy.

### Process Types
* **Foreground process** — interacts directly with the user.
* **Background process** — runs without direct user interaction.
* **Daemon** — a background process that provides a service or performs a specific system function.

### Process States
A process can be in different states during its lifetime, such as:
* Running
* Sleeping
* Stopped
* Zombie

### Key Takeaways
* A process is a running program.
* Each process has a unique PID.
* Processes can have parent-child relationships.
* Daemons provide background services.
* Linux manages process execution and resource usage.

---

# Package Management
Linux software is commonly distributed as **packages**. A package contains the files and information required to install and maintain a software application.
A **package manager** is used to manage these packages.

### Main Functions
Package management allows software to be:
* Installed
* Updated
* Removed
* Configured
* Searched for

Package managers also handle **dependencies**, which are other software components required by an application.

---

## Package Formats
Different Linux distributions use different package formats and package-management systems.

### Debian Packages
Debian and Debian-based distributions such as Ubuntu commonly use the **`.deb` package format**.
**DPKG** is the underlying package management tool for `.deb` packages, while **APT** provides higher-level package management and dependency handling.
```text
Debian / Ubuntu
       ↓
    .deb
       ↓
     DPKG
       ↓
      APT
```

### RPM Packages
**RPM (Red Hat Package Manager)** is a package format commonly associated with Red Hat-based distributions.
Examples include:
* Red Hat Enterprise Linux
* Fedora
* CentOS

Modern Red Hat-based systems commonly use higher-level tools such as **DNF** to manage RPM packages and dependencies.
```text
Red Hat / Fedora
       ↓
     .rpm
       ↓
      RPM
       ↓
      DNF
```

### Arch Packages
Arch Linux uses its own package management system, **Pacman**, for installing and managing software.

---

