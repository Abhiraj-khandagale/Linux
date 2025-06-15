🧠 CPU Information
🔹 lscpu
bash
Copy
Edit
lscpu
📌 Displays detailed CPU architecture info (cores, threads, vendor, etc.)

🔹 cat /proc/cpuinfo
bash
Copy
Edit
cat /proc/cpuinfo
📌 Lists raw CPU info per core from the /proc virtual file system.

💾 Memory (RAM) Information
🔹 free -h
bash
Copy
Edit
free -h
📌 Shows free and used memory in a human-readable format.

🔹 cat /proc/meminfo
bash
Copy
Edit
cat /proc/meminfo
📌 Detailed memory stats including buffers, cached memory, and swap.

💽 Disk and Storage
🔹 lsblk
bash
Copy
Edit
lsblk
📌 Displays block devices (hard drives, partitions) in a tree view.

🔹 df -h
bash
Copy
Edit
df -h
📌 Shows disk space usage on mounted file systems.

🔹 fdisk -l
bash
Copy
Edit
sudo fdisk -l
📌 Lists all available disk partitions.

🔹 du -sh /path/to/dir
bash
Copy
Edit
du -sh /var/log
📌 Shows disk usage of a directory.

💽 Mount Information
🔹 mount
bash
Copy
Edit
mount
📌 Displays all currently mounted filesystems.

🔹 findmnt
bash
Copy
Edit
findmnt
📌 Displays a nicely formatted tree of mounted filesystems.

📶 PCI Devices
🔹 lspci
bash
Copy
Edit
lspci
📌 Lists PCI devices such as network cards, sound cards, graphics.

🔹 lspci -v
bash
Copy
Edit
lspci -v
📌 Verbose output with driver and kernel module details.

🔌 USB Devices
🔹 lsusb
bash
Copy
Edit
lsusb
📌 Lists USB devices connected to the system.

🌐 Hardware Summary Tool
🔹 lshw
bash
Copy
Edit
sudo lshw
📌 Displays full system hardware info (CPU, memory, network, storage, etc.)

🔹 lshw -short
bash
Copy
Edit
sudo lshw -short
📌 Compact summary view.

🧰 DMI Table (BIOS & System Info)
🔹 dmidecode
bash
Copy
Edit
sudo dmidecode
📌 Reads system hardware information from the BIOS.

🔹 dmidecode -t memory
bash
Copy
Edit
sudo dmidecode -t memory
📌 Show only memory-related info.

🔧 Other Useful Tools
🔹 inxi
bash
Copy
Edit
inxi -Fxz
📌 Friendly tool showing full hardware summary (install with sudo apt install inxi).

🔹 hwinfo
bash
Copy
Edit
sudo hwinfo
📌 Detailed hardware probe utility (install on openSUSE, Debian-based).

🧪 Temperature & Sensors
🔹 sensors
bash
Copy
Edit
sensors
📌 Displays CPU temperature and fan speed (install via lm-sensors).

🔹 watch -n 2 sensors
bash
Copy
Edit
watch -n 2 sensors
📌 Live temperature monitoring every 2 seconds.

🖥️ Graphics Information
🔹 glxinfo | grep "OpenGL renderer"
bash
Copy
Edit
glxinfo | grep "OpenGL renderer"
📌 Show GPU (graphics card) renderer info. Install via mesa-utils.

🧩 System Summary (One-liner)
🔹 uname -a
bash
Copy
Edit
uname -a
📌 Kernel version, architecture, and system type.

🔹 hostnamectl
bash
Copy
Edit
hostnamectl
📌 System hostname, OS, kernel, and architecture.

