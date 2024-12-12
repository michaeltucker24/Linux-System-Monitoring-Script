# Linux System Monitoring Script

This project is a command-line script designed for Linux to monitor system performance, including CPU, memory, disk usage, and uptime. The script provides a snapshot of system resources, making it useful for managing and analyzing resource consumption on Linux servers.

---

## Screenshots and Descriptions

### 1. Script Initialization
![image](https://github.com/user-attachments/assets/394fc1a4-6e77-45f2-a83f-5275a4fc41af)
This screenshot shows the start of the `system_monitor.sh` script with a description of its purpose, setting up the file for further edits.

---

### 2. Adding CPU and Memory Usage
![image](https://github.com/user-attachments/assets/fa01ff96-86a7-482a-920a-1cf22fbec87c)
This screenshot shows the `CPU and Memory Usage` section added to `system_monitor.sh`. The script displays a summary of CPU and memory usage along with the top 10 processes consuming system resources.

---

### 3. Adding Disk Usage Monitoring
![image](https://github.com/user-attachments/assets/e0a1c65f-6fdb-43fb-9acb-d64372edc402)
This screenshot shows the `Disk Usage` section in `system_monitor.sh`. The script uses `df -h` to display disk usage in a human-readable format, providing information on used and available disk space.

---

### 4. Adding System Uptime Monitoring
![image](https://github.com/user-attachments/assets/d4078d43-6b4b-48ed-82e0-5071eee6262c)
This screenshot shows the `System Uptime` section added to `system_monitor.sh`. The script uses the `uptime` command to display how long the system has been running and the current load averages, providing insights into system stability.

---

### 5. Running the Script
![Screenshot 2024-12-12 at 2 03 55 PM](https://github.com/user-attachments/assets/74fd22ab-b267-40a3-9098-b6553d6e334e)

This screenshot shows the output of `system_monitor.sh` after running it. The script displays sections for CPU and memory usage, disk usage, and system uptime, providing a quick overview of system resources and performance.

---

## Usage Instructions

1. **Make the Script Executable**:
   \`\`\`bash
   chmod +x system_monitor.sh
   \`\`\`

2. **Run the Script**:
   \`\`\`bash
   ./system_monitor.sh
   \`\`\`

3. Follow the output sections to view system statistics for CPU, memory, disk, and uptime.

## What I Learned

- Using \`top\`, \`df\`, and \`uptime\` commands to gather system statistics.
- Writing interactive Bash scripts for system management on Linux.
- Applying file permissions with \`chmod\` and creating and editing scripts using \`nano\`.

---

This project serves as a foundation for building more advanced system management scripts in Linux. Future additions could include monitoring network traffic, memory usage trends, or active process monitoring.
