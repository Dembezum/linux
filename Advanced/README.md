# Task 1: Shell Scripting

### Objective

* **Learn how to write and execute shell scripts.**

**Commands to Practice:** `bash`, `sh`, `chmod +x`

**Task Description:**

* Write a simple shell script that prints "Hello, World!" to the terminal.
* Make the script executable using `chmod +x`.
* Execute the script using `./script_name.sh`.

**Why:** Shell scripting is a powerful tool for automating repetitive tasks and
managing system operations. Learning how to write and execute shell scripts can
significantly enhance your productivity and efficiency in a Linux environment.

### Example

1. **Create a Shell Script:**

   Open your favorite text editor and create a file named `hello_world.sh` with
   the following content:

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

* **Consult the man pages:** Use `man <command>` to read the manual for each command (e.g., `man bash`). [Linux Man Pages](https://man7.org/linux/man-pages/)
* **Search online:** Websites like [Stack Overflow](https://stackoverflow.com/) and [Linux forums](https://www.linuxquestions.org/questions/) can provide answers to common issues.
* **Practice with examples:** Try different options and arguments with each command to see how they work.
* **Ask for help:** If you're in a learning group or class, don't hesitate to ask peers or instructors for assistance.

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

### Example

1. **Set ACLs:**

   ```sh
   setfacl -m u:username:rwx filename
   ```

2. **View ACLs:**

   ```sh
   getfacl filename
   ```

3. **Modify umask:**

   ```sh
   umask 022
   ```

### Help and Progression

If you're stuck:

* **Consult the man pages:** Use `man <command>` to read the manual for each command (e.g., `man setfacl`). [Linux Man Pages](https://linux.die.net/man/)
* **Search online:** Websites like [Stack Overflow](https://stackoverflow.com/) and [Linux forums](https://www.linuxquestions.org/questions/) can provide answers to common issues.
* **Practice with examples:** Try different options and arguments with each command to see how they work.
* **Ask for help:** If you're in a learning group or class, don't hesitate to ask peers or instructors for assistance.

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

### Example

1. **Display Network Interfaces:**

   ```sh
   ip addr show
   ```

2. **Configure Network Interface:**

   ```sh
   ip addr add 192.168.1.100/24 dev eth0
   ```

3. **Manage Network Connections:**

   ```sh
   nmcli device status
   ```

4. **View Routing Table:**

   ```sh
   route -n
   ```

### Help and Progression

If you're stuck:

* **Consult the man pages:** Use `man <command>` to read the manual for each command (e.g., `man ip`). [Linux Man Pages](https://man7.org/linux/man-pages/)
* **Search online:** Websites like [Stack Overflow](https://stackoverflow.com/) and [Linux forums](https://www.linuxquestions.org/questions/) can provide answers to common issues.
* **Practice with examples:** Try different options and arguments with each command to see how they work.
* **Ask for help:** If you're in a learning group or class, don't hesitate to ask peers or instructors for assistance.
