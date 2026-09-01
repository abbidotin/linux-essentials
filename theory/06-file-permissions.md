# File Permissions
Linux uses a **file permission system** to control access to files and directories.
Permissions determine what users are allowed to do with a particular resource.

## Permission Types
There are three basic types of permissions:
| Permission      | Meaning                       |
| --------------- | ----------------------------- |
| **Read (r)**    | View the contents of a file   |
| **Write (w)**   | Modify the contents of a file |
| **Execute (x)** | Execute a file                |

For directories, these permissions have slightly different meanings.
* **Read** — view the contents of a directory
* **Write** — create, delete, or modify entries
* **Execute** — access the directory and its contents

---

## Permission Categories
Permissions are assigned to three categories:
* **User (u)** — the owner of the file
* **Group (g)** — members of the file's group
* **Others (o)** — all other users

For example:
```text
User     → rwx
Group    → r-x
Others   → r--
```

---

## File Ownership
Every file and directory has an associated:
* **User owner**
* **Group owner**

The owner and group information work together with permissions to control access to the resource.

---

## Permission Representation
Permissions can be represented using letters:
```text
rwxr-xr--
```

They are divided into three sets:
```text
rwx | r-x | r--
 ↓     ↓     ↓
User  Group Others
```

Permissions can also be represented numerically using values:
| Permission | Value |
| ---------- | ----: |
| Read       |     4 |
| Write      |     2 |
| Execute    |     1 |

The values are combined to represent a permission set.

---

## Why File Permissions Matter
File permissions help protect system and user data from unauthorized access or modification.
They are particularly important for:
* User privacy
* System security
* Shared systems
* Server environments
* Cloud infrastructure

Incorrect permissions can allow users to access or modify resources they should not have access to.

---

## Key Takeaways
* Linux uses permissions to control access to files and directories.
* The three basic permissions are **read, write, and execute**.
* Permissions apply to the **user, group, and others**.
* Every file has a user owner and a group owner.
* Permissions can be represented symbolically or numerically.
* Proper permissions are an important part of Linux system security.

## References
* Cisco Networking Academy — Linux Essentials
