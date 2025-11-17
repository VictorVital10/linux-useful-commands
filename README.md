# Useful and Versatile Linux Commands:penguin:

> **Developed By:** Victor Vital https://www.linkedin.com/in/victorvitall

## Files and Directories :open_file_folder:

---

**pwd** | Prints the current working directory.

**ls** | Lists files and directories in the current location.

**cat** | Display the contents of text files (`.txt`).

**more** | View `.txt` files one screen at a time, useful for reading long files.

**cp** | Copies files or directories.

**mv** | Moves or renames files or directories.

**rm** | Deletes files or directories.

**nano** | Command line text editor for creating or editing files.

**echo** | Prints text to the terminal.

**mkdir** | Creates a new directory in the file system.

**touch** | Creates a new empty file or updates the timestamp of an existing file.

**tar -czf** | Compress files into a `.tar.gz`archive.

**tar -xzf** | Extract files from a `.tar.gz` archive.

## Processes :gear:

---

**find [/ -name]** | Searches for files or directories by name.

**top** | Display a real-time view of system performance (active processes, CPU and memory usage).

**ps aux** | Display detailed information about all running processes.

**kill [signal] [PID]** | Terminate processess by sending them a signal. 

**grep [name]** | Searches for patterns within text or command output.

**head** | Display the first lines of a file or command output.

**tail** | Display the last lines of a file or command output, useful for monitoring logs (`-f` to follow updates in real time).

**diff** | Compares two files line by line and shows the differences.

## PERMISSIONS :closed_lock_with_key:

---

**chmod** | Changes the permissions of a file or directory.

**su [username]** | Switch to another user account.

**sudo** | Executes commands with administrative privileges.

**adduser [username]** | Creates a new user account. 

**usermod** | Modify an existing user account (`-l` to change the login name, `-d` to change the home directory).

**passwd** | Used to change a user's password.

**userdel [username]** | Deletes a user account from the system.

**groupadd [groupname]** | Create a new group.

**groupmod** | Modify an existig group, similar to usermod (`-n` to change the name of a group, `-g` to change the GID of a group.)

**groupdel [groupname]** | Deletes an existing group from the system.

**groups [username]** | Display the groups a user belongs to.

