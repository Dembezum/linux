# Task 1: Shell Scripting

### Objective

* **Learn how to write and execute shell scripts.**

**Commands to Practice:** `bash`, `sh`, `chmod +x`

**Task Description:**

* Write a simple shell script that prints "Hello, World!" to the terminal.
* Make the script executable using `chmod +x`.
* Execute the script using `./script_name.sh`.

**Why:** Shell scripting is a powerful tool for automating repetitive tasks and managing system operations. Learning how to write and execute shell scripts can significantly enhance your productivity and efficiency in a Linux environment.

### Example

1. **Create a Shell Script:**

   Open your favorite text editor and create a file named `hello_world.sh` with the following content:

   ```bash
   #!/bin/bash
   echo "Hello, World!"
   ```

2. **Make the Script Executable:**

   Use the `chmod` command to make the script executable:

   ```sh
   chmod +x hello_world.sh
   ```

3. **Execute the Script:**

   Run the script using the following command:

   ```sh
   ./hello_world.sh
   ```

   You should see the output:

   ```sh
   Hello, World!
   ```

### Help and Progression

If you're stuck:

* **Consult the man pages:** Use `man <command>` to read the manual for each command (e.g., `man bash`).
* **Search online:** Websites like Stack Overflow and Linux forums can provide answers to common issues.
* **Practice with examples:** Try different options and arguments with each command to see how they work.
* **Ask for help:** If you're in a learning group or class, don't hesitate to ask peers or instructors for assistance.

#### Create your own little script Now you will create your own little shell

script. You should decide what it should do, it could count from 1 to 10,
display basic addition, multiplication or division, make automate creating a
user, making directories or creating a file. You can also make a script that
will display the current date and time. The possibilities are endless.

> It's now up to you to decide what your script will do. You can always ask for
> help or inspiration. Search the internet yourself, and figure out how to
> complete the task on your own. It's a great way to learn!

**Task Description:**

* Create a bash script that includes some basic programming paradigms. For
example, you can include loops, conditional statements, and functions.
* Make the script executable using `chmod +x`.
* Execute the script using `./script_name.sh`.

---

# Task 2: Advanced Permissions

### Objective

* **Master advanced file and directory permissions.**

**Commands to Practice:** `setfacl`, `getfacl`, `umask`

**Task Description:**

* Set Access Control Lists (ACLs) on files and directories using `setfacl`.
* View ACLs using `getfacl`.
* Modify the default file creation permissions using `umask`.

**Why:** Advanced permissions management is crucial for fine-grained access
control. ACLs provide more flexibility than traditional Unix permissions,
allowing you to specify permissions for individual users and groups.
Understanding `umask` helps you control the default permissions for newly
created files and directories.

---

# Task 3: Network Configuration

### Objective

* **Configure and manage network settings.**

**Commands to Practice:** `ip`, `nmcli`, `ifconfig`, `route`

**Task Description:**

* Display and configure network interfaces using `ip` and `ifconfig`.
* Manage network connections using `nmcli`.
* View and modify the routing table using `route`.

**Why:** Network configuration is essential for ensuring proper connectivity
and communication between systems. These commands help you configure network
interfaces, manage connections, and control routing, enabling you to set up and
troubleshoot network settings effectively.

---

# Task 4: System Monitoring and Performance Tuning

### Objective

* **Monitor system performance and tune system settings.**

**Commands to Practice:** `htop`, `iotop`, `vmstat`, `sysctl`

**Task Description:**

* Monitor system processes and resource usage using `htop`.
* Monitor disk I/O usage using `iotop`.
* View system performance statistics using `vmstat`.
* Modify kernel parameters at runtime using `sysctl`.

**Why:** System monitoring and performance tuning are critical for maintaining
system stability and efficiency. These commands provide insights into system
resource usage and performance, allowing you to identify bottlenecks and
optimize system settings for better performance.

---

# Task 5: Package Management

### Objective

* **Master package management for software installation and updates.**

**Commands to Practice:** `apt`, `yum`, `dnf`, `snap`

**Task Description:**

* Install, update, and remove packages using `apt` (Debian-based systems) or
`yum`/`dnf` (Red Hat-based systems).
* Manage snap packages using `snap`.

**Why:** Package management is essential for installing and maintaining
software on your system. These commands help you manage software packages,
ensuring that you can easily install, update, and remove applications as
needed.

---

# Task 6: Backup and Restore

### Objective

* **Learn how to backup and restore files and directories.**

**Commands to Practice:** `tar`, `rsync`, `dd`

**Task Description:**

* Create a compressed archive of a directory using `tar`.
* Synchronize files and directories using `rsync`.
* Create and restore disk images using `dd`.

**Why:** Backup and restore operations are crucial for data protection and
recovery. These commands help you create backups of important files and
directories, synchronize data between systems, and create disk images for
complete system backups, ensuring that you can recover from data loss or system
failures.
