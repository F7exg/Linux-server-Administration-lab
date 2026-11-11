# File and Directory Management

## Overview
Hands-on Linux file management and permission administration
using Red Hat Enterprise Linux 9.6.

## Environment
- OS: Red Hat Enterprise Linux 9.6
- Virtualization: VMware Workstation
- Access: SSH via MobaXterm

## Practical Tasks

### 1. File and Directory Operations
| Command | Purpose |
|---|---|
| pwd | Display current directory |
| ls -la | List files and directories |
| mkdir | Create directories |
| touch | Create empty files |
| echo | Write text into files |
| cat | Display file contents |
| cp | Copy files |
| mv | Move and rename files |
| rm | Remove files |

### 2. File Permissions
| Command | Purpose |
|---|---|
| chmod 600 | Set owner read/write permissions |
| chmod u+x | Add execute permission for owner |
| chmod u-w | Remove write permission for owner |
| chmod g+r | Add read permission for group |
| chmod 640 | Set numeric file permissions |
| chmod 750 | Set directory permissions |

### 3. Ownership Management
| Command | Purpose |
|---|---|
| id | Display user and group information |
| chown :devops | Change file group ownership |
| ls -l | Inspect ownership and permissions |
| stat | Display detailed file information |

## Permissions Reference

| Permission | Value | Description |
|---|---|---|
| Read (r) | 4 | Read file contents |
| Write (w) | 2 | Modify file contents |
| Execute (x) | 1 | Execute a file |
| Owner (u) | - | File owner |
| Group (g) | - | Owning group |
| Others (o) | - | Other users |

## Practical Results
- Created and managed files and directories.
- Practiced copying, moving, renaming and deleting files.
- Applied symbolic and numeric permissions.
- Changed group ownership using chown.
- Configured directory permissions.
- Verified ownership and permissions using ls and stat.

## Skills Demonstrated
- Linux File System Management
- File and Directory Operations
- Linux Permissions and Ownership
- User and Group Administration
- Command-Line Administration
