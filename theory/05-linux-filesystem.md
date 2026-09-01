# Linux Filesystems
A **filesystem** is the method used by an operating system to organize and manage data on a storage device.
Linux uses a **hierarchical filesystem structure**, where everything starts from the **root directory `/`**.

## Filesystem Structure
```text
/
├── /bin
├── /boot
├── /dev
├── /etc
├── /home
├── /lib
├── /media
├── /mnt
├── /opt
├── /root
├── /tmp
├── /usr
└── /var
```


## Important Directories
| Directory | Purpose                         |
| --------- | ------------------------------- |
| `/`       | Root of the filesystem          |
| `/bin`    | Essential user commands         |
| `/boot`   | Files required for booting      |
| `/dev`    | Device files                    |
| `/etc`    | System configuration files      |
| `/home`   | Users' personal directories     |
| `/lib`    | Essential shared libraries      |
| `/media`  | Mount point for removable media |
| `/mnt`    | Temporary mount point           |
| `/opt`    | Optional software               |
| `/root`   | Home directory of the root user |
| `/tmp`    | Temporary files                 |
| `/usr`    | User programs and data          |
| `/var`    | Variable data such as logs      |


## Files and Directories
Linux treats files and directories as part of the same hierarchical structure.
A directory can contain:
* Files
* Other directories
* Subdirectories

This structure makes it possible to organize system and user data efficiently.


## Paths
A **path** identifies the location of a file or directory.

### Absolute Path
An absolute path starts from the root directory `/`.
Example:
```text
/home/user/Documents
```

### Relative Path
A relative path describes a location from the current directory.
Example:
```text
Documents/file.txt
```

## Linux Filesystem Types
Linux supports different filesystem types.
Some common examples are:
* **ext4**
* **XFS**
* **Btrfs**

Different filesystems provide different features for storing and managing data.


## Key Takeaways
* A filesystem organizes and manages data.
* Linux uses a hierarchical filesystem structure.
* `/` is the root of the filesystem.
* Different directories have specific purposes.
* Paths can be absolute or relative.
* Linux supports multiple filesystem types.


## References
* Cisco Networking Academy — Linux Essentials
