ＬＩＮＵＸ ＣＯＭＭＡＮＤＳ

Linux is an operating system, like Windows or macOS, that helps your computer run and manage its hardware and software. 

    • Open Source: Anyone can view, modify, and distribute the source code. It’s free to use!
    • Kernel: The core part of Linux manages everything, like memory and processes.
    • Distributions: Different versions of Linux (like Ubuntu, Fedora, and Debian) that package the kernel with additional software and tools.
    • User-Friendly: While it can be technical, many distributions with graphical interfaces are designed to be easy to use.

Basic Commands
    1. ls
        ◦ Explanation: Lists files and directories in the current directory.
        ◦ Example: ls -l (lists in long format)
    2. cd
        ◦ Explanation: Changes the current directory.
        ◦ Example: cd /home/user (navigates to the specified directory)
    3. pwd
        ◦ Explanation: Prints the current working directory.
        ◦ Example: pwd (displays the full path of the current directory)
    4. mkdir
        ◦ Explanation: Creates a new directory.
        ◦ Example: mkdir new_folder (creates a folder named "new_folder")
    5. rmdir
        ◦ Explanation: Removes an empty directory.
        ◦ Example: rmdir old_folder (removes "old_folder" if it's empty)
    6. rm
        ◦ Explanation: Removes files or directories.
        ◦ Example: rm file.txt (deletes "file.txt")
    7. cp
        ◦ Explanation: Copies files or directories.
        ◦ Example: cp file.txt backup.txt (copies "file.txt" to "backup.txt")
    8. mv
        ◦ Explanation: Moves or renames files or directories.
        ◦ Example: mv oldname.txt newname.txt (renames "oldname.txt" to "newname.txt")
    9. touch
        ◦ Explanation: Creates an empty file or updates the timestamp of an existing file.
        ◦ Example: touch newfile.txt (creates "newfile.txt")
    10.  cat
        ◦ Explanation: Concatenates and displays file content.
        ◦ Example: cat file.txt (shows the content of "file.txt").
11. more
        ◦ Views the content of a file one screen at a time.
        ◦ Example: more file.txt
    12.  less
        ◦ Similar to more, but allows backward navigation.
        ◦ Example: less file.txt
    13.  head
        ◦ Displays the first few lines of a file.
        ◦ Example: head file.txt
    14.  tail
        ◦ Displays the last few lines of a file.
        ◦ Example: tail file.txt
    15.  grep
        ◦ Searches for a specific pattern in files.
        ◦ Example: grep "text" file.txt
    16.  find
        ◦ Searches for files and directories.
        ◦ Example: find /home -name "*.txt"
    17. locate
        ◦ Quickly finds files by name.
        ◦ Example: locate file.txt
    18.  wc
        ◦ Counts lines, words, and characters in a file.
        ◦ Example: wc file.txt
    19.  diff
        ◦ Compares two files line by line.
        ◦ Example: diff file1.txt file2.txt
    20.  sort
        ◦ Sorts lines in a file.
        ◦ Example: sort file.txt

    21.  df
        ◦ Displays disk space usage.
        ◦ Example: df -h
    22.  du
        ◦ Estimates file and directory space usage.
        ◦ Example: du -sh *
    23.  free
        ◦ Displays memory usage.
        ◦ Example: free -h
    24.  top
        ◦ Displays real-time system processes.
        ◦ Example: top
    25.  ps
        ◦ Displays currently running processes.
        ◦ Example: ps aux
    26.  kill
        ◦ Terminates a process by its PID.
        ◦ Example: kill 1234
    27.  uname
        ◦ Displays system information.
        ◦ Example: uname -a
    28.  uptime
        ◦ Shows how long the system has been running.
        ◦ Example: uptime
    29.  who
        ◦ Displays who is logged in.
        ◦ Example: who
    30.  history
        ◦ Shows the command history.
        ◦ Example: history
    31.  chmod
        ◦ Changes file permissions.
        ◦ Example: chmod 755 script.sh
    32.  chown
        ◦ Changes file owner and group.
        ◦ Example: chown user:group file.txt
    33.  chgrp
        ◦ Changes the group ownership of a file.
        ◦ Example: chgrp groupname file.txt
    34.  stat
        ◦ Displays detailed information about a file.
        ◦ Example: stat file.txt
    35.  umask
        ◦ Sets default file permissions for newly created files.
        ◦ Example: umask 022

    36.  ping
        ◦ Tests network connectivity to a host.
        ◦ Example: ping google.com
    37.  ifconfig
        ◦ Displays network interface configuration (deprecated in favor of ip).
        ◦ Example: ifconfig
    38.  ip
        ◦ Displays or configures network interfaces.
        ◦ Example: ip addr
    39.  wget
        ◦ Downloads files from the web.
        ◦ Example: wget http://example.com/file.zip
    40.  curl
        ◦ Transfers data from or to a server.
        ◦ Example: curl -O http://example.com/file.zip
    41.  ssh
        ◦ Connects to a remote server securely.
        ◦ Example: ssh user@hostname
    42.  scp
        ◦ Securely copies files between hosts.
        ◦ Example: scp file.txt user@hostname:/path/to/destination
    43.  tar
        ◦ Archives files into a single file.
        ◦ Example: tar -czvf archive.tar.gz folder/
    44.  zip
        ◦ Compresses files into a zip archive.
        ◦ Example: zip archive.zip file1.txt file2.txt
    45.  unzip
        ◦ Extracts files from a zip archive.
        ◦ Example: unzip archive.zip
    46.  alias
        ◦ Creates shortcuts for commands.
        ◦ Example: alias ll='ls -la'
    47.  echo
        ◦ Displays a line of text or variable value.
        ◦ Example: echo "Hello, World!"
    48.  clear
        ◦ Clears the terminal screen.
        ◦ Example: clear
    49.  exit
        ◦ Exits the terminal or shell.
        ◦ Example: exit
    50.  man
        ◦ Displays the manual for a command.
        ◦ Example: man ls

INTERMEDIATE COMMANDS

1.cp -r
        ◦ Explanation: Recursively copies directories.
        ◦ Example: cp -r source_dir/ destination_dir/
    2. mv -i
        ◦ Explanation: Moves or renames files, prompts before overwriting.
        ◦ Example: mv -i oldname.txt newname.txt
    3. rsync
        ◦ Explanation: Synchronizes files and directories.
        ◦ Example: rsync -avz source/ destination/
    4. ln
        ◦ Explanation: Creates links to files.
        ◦ Example: ln -s original.txt link.txt (creates a symbolic link)
    5. tree
        ◦ Explanation: Displays directory structure in a tree format.
        ◦ Example: tree /path/to/directory
    6. basename
        ◦ Explanation: Strips directory and suffix from filenames.
        ◦ Example: basename /path/to/file.txt (returns "file.txt")
    7. dirname
        ◦ Explanation: Strips the last component from a file name.
        ◦ Example: dirname /path/to/file.txt (returns "/path/to")
    8. shred
        ◦ Explanation: Securely deletes files by overwriting them.
        ◦ Example: shred -u file.txt
    9. file
        ◦ Explanation: Determines the type of a file.
        ◦ Example: file script.sh
    10. tar -xvf
        ◦ Explanation: Extracts files from a tar archive.
        ◦ Example: tar -xvf archive.tar
    11. awk
        ◦ Explanation: A programming language for pattern scanning and processing.
        ◦ Example: awk '{print $1}' file.txt (prints the first column)
    12. sed
        ◦ Explanation: Stream editor for filtering and transforming text.
        ◦ Example: sed 's/old/new/g' file.txt (replaces "old" with "new")
    13. cut
        ◦ Explanation: Cuts sections from each line of files.
        ◦ Example: cut -d':' -f1 /etc/passwd (displays the first field from each line)
    14. sort -r
        ◦ Explanation: Sorts lines in reverse order.
        ◦ Example: sort -r file.txt
    15. uniq
        ◦ Explanation: Filters out repeated lines in a file.
        ◦ Example: uniq file.txt
    16. tr
        ◦ Explanation: Translates or deletes characters.
        ◦ Example: tr 'a-z' 'A-Z' < file.txt (converts lowercase to uppercase)
    17. paste
        ◦ Explanation: Merges lines of files.
        ◦ Example: paste file1.txt file2.txt
    18. join
        ◦ Explanation: Joins lines of two files based on a common field.
        ◦ Example: join file1.txt file2.txt
    19. diff -u
        ◦ Explanation: Shows differences between files in unified format.
        ◦ Example: diff -u file1.txt file2.txt
    20. wc -l
        ◦ Explanation: Counts the number of lines in a file.
        ◦ Example: wc -l file.txt
    21. htop
        ◦ Explanation: An interactive process viewer.
        ◦ Example: htop
    22. vmstat
        ◦ Explanation: Reports virtual memory statistics.
        ◦ Example: vmstat 1 (updates every second)
    23. iostat
        ◦ Explanation: Reports CPU and I/O statistics.
        ◦ Example: iostat
    24. netstat
        ◦ Explanation: Displays network connections and statistics.
        ◦ Example: netstat -tuln
    25. lsof
        ◦ Explanation: Lists open files and the processes that opened them.
        ◦ Example: lsof
    26. df -i
        ◦ Explanation: Displays inode usage.
        ◦ Example: df -i
    27. uptime
        ◦ Explanation: Shows how long the system has been running.
        ◦ Example: uptime
    28. dmesg
        ◦ Explanation: Displays kernel-related messages.
        ◦ Example: dmesg | less
    29. systemctl
        ◦ Explanation: Controls the systemd system and service manager.
        ◦ Example: systemctl status apache2
    30. service
        ◦ Explanation: Manages services in older systems.
        ◦ Example: service nginx restart

    31. curl -I
        ◦ Explanation: Fetches HTTP headers from a URL.
        ◦ Example: curl -I http://example.com
    32. nslookup
        ◦ Explanation: Queries DNS to obtain domain name or IP address.
        ◦ Example: nslookup example.com
    33. dig
        ◦ Explanation: DNS lookup utility.
        ◦ Example: dig example.com
    34. ftp
        ◦ Explanation: File Transfer Protocol client.
        ◦ Example: ftp ftp.example.com
    35. scp -r
        ◦ Explanation: Securely copies directories between hosts.
        ◦ Example: scp -r dir user@hostname:/path
    36. ssh-keygen
        ◦ Explanation: Generates SSH keys for secure access.
        ◦ Example: ssh-keygen -t rsa
    37. iptables
        ◦ Explanation: Configures the Linux kernel firewall.
        ◦ Example: iptables -L (lists current rules)
    38. traceroute
        ◦ Explanation: Traces the route packets take to a network host.
        ◦ Example: traceroute google.com
    39. ping -c
        ◦ Explanation: Pings a host a specified number of times.
        ◦ Example: ping -c 4 google.com
    40. wget -r
        ◦ Explanation: Recursively downloads files from the web.
        ◦ Example: wget -r http://example.com
    41. man -k
        ◦ Explanation: Searches the manual page descriptions.
        ◦ Example: man -k copy
    42. alias
        ◦ Explanation: Creates shortcuts for commands.
        ◦ Example: alias ll='ls -la'
    43. unalias
        ◦ Explanation: Removes an alias.
        ◦ Example: unalias ll
    44. export
        ◦ Explanation: Sets environment variables.
        ◦ Example: export PATH=$PATH:/new/path
    45. crontab -l
        ◦ Explanation: Lists scheduled cron jobs.
        ◦ Example: crontab -l
    46. crontab -e
        ◦ Explanation: Edits the crontab file.
        ◦ Example: crontab -e
    47. chmod +x
        ◦ Explanation: Makes a script executable.
        ◦ Example: chmod +x script.sh
    48. history | grep
        ◦ Explanation: Searches command history.
        ◦ Example: history | grep ssh
    49. echo $PATH
        ◦ Explanation: Displays the current PATH environment variable.
        ◦ Example: echo $PATH
    50. shutdown
        ◦ Explanation: Shuts down the system.
        ◦ Example: shutdown now


ADVANCE COMMANDS
    1. sudo
        ◦ Explanation: Executes commands with superuser privileges.
        ◦ Example: sudo apt update
    2. visudo
        ◦ Explanation: Edits the sudoers file safely.
        ◦ Example: visudo
    3. chroot
        ◦ Explanation: Changes the root directory for a command.
        ◦ Example: chroot /newroot /bin/
    4. systemctl
        ◦ Explanation: Controls the systemd system and service manager.
        ◦ Example: systemctl restart nginx
    5. journalctl
        ◦ Explanation: Views logs from the systemd journal.
        ◦ Example: journalctl -u sshd
    6. useradd
        ◦ Explanation: Creates a new user.
        ◦ Example: sudo useradd newuser
    7. usermod
        ◦ Explanation: Modifies a user account.
        ◦ Example: sudo usermod -aG sudo newuser
    8. userdel
        ◦ Explanation: Deletes a user account.
        ◦ Example: sudo userdel newuser
    9. groupadd
        ◦ Explanation: Creates a new group.
        ◦ Example: sudo groupadd newgroup
    10. passwd
        ◦ Explanation: Changes a user’s password.
        ◦ Example: sudo passwd newuser
    11. iptables
        ◦ Explanation: Configures the Linux kernel firewall.
        ◦ Example: sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
    12. nmap
        ◦ Explanation: Network exploration and security auditing tool.
        ◦ Example: nmap -sP 192.168.1.0/24
    13. tcpdump
        ◦ Explanation: Captures network packets.
        ◦ Example: sudo tcpdump -i eth0
    14. ssh-keygen
        ◦ Explanation: Generates SSH key pairs for secure access.
        ◦ Example: ssh-keygen -t rsa
    15. rsync
        ◦ Explanation: Synchronizes files and directories between locations.
        ◦ Example: rsync -avz /source/ /destination/
    16. fail2ban
        ◦ Explanation: Protects servers from brute-force attacks.
        ◦ Example: sudo fail2ban-client status
    17. whois
        ◦ Explanation: Queries domain registration information.
        ◦ Example: whois example.com
    18. dig
        ◦ Explanation: DNS lookup utility.
        ◦ Example: dig example.com
    19. curl
        ◦ Explanation: Transfers data from or to a server.
        ◦ Example: curl -O http://example.com/file
    20. scp
        ◦ Explanation: Securely copies files between hosts.
        ◦ Example: scp file.txt user@hostname:/path
    21. lsof
        ◦ Explanation: Lists open files and processes.
        ◦ Example: lsof | grep process_name
    22. strace
        ◦ Explanation: Traces system calls and signals.
        ◦ Example: strace -p PID
    23. nohup
        ◦ Explanation: Runs a command immune to hangups.
        ◦ Example: nohup long_running_command &
    24. at
        ◦ Explanation: Schedules a command to run once at a specific time.
        ◦ Example: echo "command" | at 10:00
    25. cron
        ◦ Explanation: Schedules recurring tasks.
        ◦ Example: crontab -e (to edit the cron jobs)
    26. nice
        ◦ Explanation: Runs a command with modified scheduling priority.
        ◦ Example: nice -n 10 command
    27. renice
        ◦ Explanation: Changes the priority of running processes.
        ◦ Example: renice 10 -p PID
    28. bg
        ◦ Explanation: Resumes a suspended job in the background.
        ◦ Example: bg %1


    29. fg
        ◦ Explanation: Brings a background job to the foreground.
        ◦ Example: fg %1
    30. jobs
        ◦ Explanation: Lists active jobs in the current shell session.
        ◦ Example: jobs

       31.fdisk
        ◦ Explanation: Partition table manipulator for Linux.
        ◦ Example: sudo fdisk /dev/sda
    32. mkfs
        ◦ Explanation: Creates a filesystem on a partition.
        ◦ Example: sudo mkfs.ext4 /dev/sda1
    33. mount
        ◦ Explanation: Mounts a filesystem.
        ◦ Example: sudo mount /dev/sda1 /mnt
    34. umount
        ◦ Explanation: Unmounts a filesystem.
        ◦ Example: sudo umount /mnt
    35. df -h
        ◦ Explanation: Displays disk space usage in a human-readable format.
        ◦ Example: df -h
    36. du -sh
        ◦ Explanation: Displays the size of a directory.
        ◦ Example: du -sh /path/to/directory
    37. tar -czvf
        ◦ Explanation: Creates a compressed archive.
        ◦ Example: tar -czvf archive.tar.gz /path/to/directory
    38. gzip
        ◦ Explanation: Compresses files using the GNU zip algorithm.
        ◦ Example: gzip file.txt
    39. gunzip
        ◦ Explanation: Decompresses .gz files.
        ◦ Example: gunzip file.txt.gz
    40. dd
        ◦ Explanation: Converts and copies files, often used for backups.
        ◦ Example: sudo dd if=/dev/sda of=/dev/sdb bs=64K

    41. awk
        ◦ Explanation: A programming language for pattern scanning and processing.
        ◦ Example: awk '{print $1}' file.txt
    42. sed
        ◦ Explanation: Stream editor for filtering and transforming text.
        ◦ Example: sed 's/old/new/g' file.txt
    43. grep -r
        ◦ Explanation: Recursively searches for a pattern in files.
        ◦ Example: grep -r "text" /path/to/dir
    44. find -exec
        ◦ Explanation: Executes a command on found files.
        ◦ Example: find . -name "*.txt" -exec rm {} \;
    45. xargs
        ◦ Explanation: Builds and executes command lines from standard input.
        ◦ Example: find . -name "*.txt" | xargs rm
    46. cut -f
        ◦ Explanation: Cuts sections from each line of files based on field delimiter.
        ◦ Example: cut -f1 -d':' /etc/passwd
    47. sort -u
        ◦ Explanation: Sorts and removes duplicate lines.
        ◦ Example: sort -u file.txt
    48. tee
        ◦ Explanation: Reads from standard input and writes to standard output and files.
        ◦ Example: echo "text" | tee file.txt
    49. env
        ◦ Explanation: Displays the environment variables.
        ◦ Example: env
    50. 
        ◦ Explanation: Starts a new instance of the  shell.
        ◦ Example: 





Senarios:

Scenario 1: System Update and Package Management
Situation: You need to update your system and install a new package.
Commands:
# Update the package list
sudo apt update

# Upgrade all installed packages
sudo apt upgrade -y

# Install a new package (e.g., curl)
sudo apt install curl -y
Scenario 2: User Management
Situation: A new employee joins the team, and you need to create a user account and add them to the sudo group.
Commands:

# Create a new user
sudo useradd -m newuser

# Set a password for the new user
sudo passwd newuser

# Add the user to the sudo group
sudo usermod -aG sudo newuser
Scenario 3: File Backup
Situation: You want to back up a directory containing important documents.
Commands:
# Create a compressed tarball of the documents directory
tar -czvf backup_documents.tar.gz /path/to/documents
Scenario 4: Network Troubleshooting
Situation: You suspect a network issue and want to check if a specific server is reachable.
Commands:
# Ping the server to check connectivity
ping -c 4 example.com

# Use traceroute to see the path taken to reach the server
traceroute example.com
Scenario 5: Disk Usage Analysis
Situation: You need to find out how much disk space is being used by a specific directory.
Commands:
# Display the size of the specified directory
du -sh /path/to/directory
Scenario 6: Process Monitoring
Situation: You want to monitor the running processes and identify any that are consuming too much CPU.
Commands:
# Use htop for an interactive process viewer
htop

# Alternatively, use top for a simpler view
top
Scenario 7: File Searching
Situation: You need to find all .log files in a directory and delete them.
Commands:
# Find and delete all .log files in the specified directory
find /path/to/directory -name "*.log" -exec rm {} \;
Scenario 8: Firewall Configuration
Situation: You need to allow SSH connections through the firewall.
Commands:
# Allow SSH connections on port 22
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT

# Save the iptables rules (depends on your distribution)
sudo iptables-save > /etc/iptables/rules.v4
Scenario 9: Scheduling a Task
Situation: You want to schedule a script to run every day at 2 AM.
Commands:
# Edit the crontab to add a new cron job
crontab -e

# Add the following line to schedule the script
0 2 * * * /path/to/script.sh

Scenario 10: SSH Key Generation
Situation: You want to generate SSH keys for secure remote access to a server.
Commands:
# Generate a new SSH key pair
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

# Copy the public key to the remote server
ssh-copy-id user@remote_server
Scenario 11: File Permission Management
Situation: You need to change the permissions of a file so that only the owner can read and write it.
Commands:

Copy
# Change the permissions of the file
chmod 600 /path/to/file.txt
Scenario 12: System Resource Monitoring
Situation: You want to check the current memory and CPU usage of your system.
Commands:
# Display memory usage
free -h

# Display CPU usage
top
Scenario 13: Creating a New Directory Structure
Situation: You need to create a directory structure for a new project.
Commands:
# Create a new project directory with subdirectories
mkdir -p /path/to/project/{src,bin,docs,tests}
Scenario 14: Viewing Log Files
Situation: You need to check the system log files for any errors.
Commands:
# View the last 50 lines of the syslog
tail -n 50 /var/log/syslog

# Follow the log file in real-time
tail -f /var/log/syslog
Scenario 15: Disk Partitioning
Situation: You need to create a new partition on a disk.
Commands:
# Start fdisk to modify the disk partition table
sudo fdisk /dev/sda

# Follow the prompts to create a new partition
Scenario 16: Package Removal
Situation: You want to remove an unused package from your system.
Commands:
# Remove a package (e.g., vim)
sudo apt remove vim -y
Scenario 17: Finding Disk Usage by Directory
Situation: You want to find which directories are using the most disk space.
Commands:
# Display disk usage for directories in the current path, sorted by size
du -ah . | sort -rh | head -n 10
Scenario 18: Searching for Text in Files
Situation: You need to find a specific word in all .txt files in a directory.
Commands:
# Search for the word "error" in all .txt files
grep -r "error" /path/to/directory/*.txt
Scenario 19: System Shutdown or Reboot
Situation: You need to shut down or reboot the system.
Commands:
# Shut down the system
sudo shutdown now

# Reboot the system
sudo reboot
Scenario 20: Creating a Symbolic Link
Situation: You want to create a symbolic link to a frequently accessed file.
Commands:
# Create a symbolic link to a file
ln -s /path/to/original/file.txt /path/to/link/file_link.txt
Scenario 21: Exporting Environment Variables
Situation: You need to set an environment variable for a session.
Commands:
# Set an environment variable
export MY_VARIABLE="my_value"

# Verify that the variable is set
echo $MY_VARIABLE
Scenario 22: Remote File Transfer
Situation: You need to transfer a file to a remote server using SCP.
Commands:
# Copy a file to a remote server
scp /path/to/local/file.txt user@remote_server:/path/to/remote/directory/
Scenario 23: Checking System Uptime
Situation: You want to check how long the system has been running since the last boot.
Commands:
# Display system uptime
uptime
Scenario 24: Monitoring Disk I/O
Situation: You want to monitor disk I/O performance on your system.
Commands:
# Use iostat to monitor disk I/O
iostat -x 1
Scenario 25: Archiving Files
Situation: You need to archive multiple files into a single compressed file.
Commands:
# Create a zip archive of multiple files
zip archive.zip file1.txt file2.txt file3.txt
Scenario 26: Configuring a Cron Job
Situation: You want to set a cron job to back up a directory every Sunday at 3 AM.
Commands:
# Edit the crontab to add the backup job
crontab -e

# Add the following line
0 3 * * 0 tar -czvf /path/to/backup/backup_$(date +\%F).tar.gz /path/to/directory
Scenario 27: Checking Open Ports
Situation: You want to see which ports are currently open on your system.
Commands:
# List open ports and associated services
sudo netstat -tuln
Scenario 28: Changing Ownership of a File
Situation: You need to change the ownership of a file to a different user.
Commands:
# Change the owner of the file
sudo chown newuser:newgroup /path/to/file.txt
Scenario 29: Creating a Backup with Rsync
Situation: You want to back up a directory to an external drive using rsync.
Commands:
# Use rsync to back up a directory
rsync -avh /path/to/source/ /path/to/destination/
Scenario 30: Using Find with Size
Situation: You want to find files larger than 100MB in a specific directory.
Commands:
# Find files larger than 100MB
find /path/to/directory -type f -size +100M








What are Cron Jobs?
Cron jobs are scheduled tasks in Unix-like operating systems that run automatically at specified intervals. The cron daemon is responsible for executing these tasks based on a configuration file called the crontab.
Crontab Syntax
A crontab entry consists of six fields:

* * * * * command_to_execute
- - - - -
| | | | |
| | | | +---- Day of the week (0 - 7)
| | | +------ Month (1 - 12)
| | +-------- Day of the month (1 - 31)
| +---------- Hour (0 - 23)
+------------ Minute (0 - 59)


1. Viewing the Crontab
To view your current user's crontab:
crontab -l
2. Editing the Crontab
To edit your crontab:
crontab -e
This opens the crontab file in the default text editor.
3. Removing the Crontab
To remove your crontab:
crontab -r
Example Cron Job Entries
Here are some practical examples of cron job entries:
1. Run a Script Every Day at Midnight


0 0 * * * /path/to/script.sh
2. Back Up a Directory Every Sunday at 3 AM


0 3 * * 0 tar -czvf /path/to/backup/backup_$(date +\%F).tar.gz /path/to/directory
3. Check Disk Space Every Hour


0 * * * * /usr/bin/df -h >> /path/to/log/disk_space.log
4. Run a Python Script Every 15 Minutes


*/15 * * * * /usr/bin/python3 /path/to/script.py
5. Clean Temporary Files Every Day at 2 AM


0 2 * * * /usr/bin/find /tmp -type f -atime +10 -delete
6. Send a Reminder Email Every Monday at 9 AM


0 9 * * 1 /usr/bin/mail -s "Weekly Reminder" user@example.com < /path/to/reminder.txt
7. Restart a Service Every Day at 4 AM

0 4 * * * /bin/systemctl restart your_service
