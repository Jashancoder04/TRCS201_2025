# Daily Diary

**Date: 25-06-2025**

# Day-1

**The difference & features of Linux and Windows.**

- Linux and Windows are both operating system.Linux is open-source,meaning its source code is freely available to any one to use and easily modify.
- Windows is a closed-source operating system and developed by microsoft.
- Linux distributions are free to download,use,and distribute.
- Windows requires a paid license for each installation.
- Linux praised for its stability and performance,especially on servers and in resource-contrainned environments.

**Download Links**

- Oracle Virtual Box

-  Microsoft Visual C++ Redistributable

- Ubuntu 

**Booting and its types**
- Waking up the computer
**Types**

| Boot Type  | Description |
|------------|-------------|
| Cold Boot  | When the computer is started from a completely powered-off state (eg, macOS). |          |
| Warm Boot  | When the computer is restarted without turning off the power (e.g.,windows).|

# Day2 

# Kernal
- It is a computer program that is a core of computer's Operating System with complete control over everything in the system.

# Shell
- It is a computer program that acts as interface between user and OS.( like Windows, macOS and Linux)

**Types of Shell**
- bash (most common shell)
- sh (original shell)
- zsh (more features)
- fish (modern)

![image](https://github.com/user-attachments/assets/7d8dd119-9012-46a4-a289-dc37f1f32db3)

**Categories**
- Command line shell
- Graphical shell

# File system structure

![image](https://github.com/user-attachments/assets/f5d199ac-044e-46ac-b7a0-711a064fa744)

# Basic shell Commands

| Command   | Description                            |
|-----------|----------------------------------------|
| `ls`      | Lists files and directories             |
| `whoami`  | Shows current logged-in user            |
| `date`    | Displays current date and time          |
| `cd`      | Changes the directory                   |
| `mkdir`   | Creates a new directory                 |
| `cat`     | Displays content of a file              |
| `touch`   | Creates an empty file                   |
| `cp`      | Copies files or directories             |
| `pwd`     | Prints current working directory        |
| `whereis` | Finds location of a command             |
| `whatis`  | Shows a brief description of a command  |
| `mv`      | Moves or renames files and directories  |

- Here are the screenshots of basic commands.
  ![VirtualBox screenshot2](https://github.com/user-attachments/assets/79d2b312-7ddf-47c5-a922-a9b9cfc07086)

![VirtualBox screenshot3](https://github.com/user-attachments/assets/0f5e6e56-d307-466b-be5b-fee04f283295)

![VirtualBox screenshot 4](https://github.com/user-attachments/assets/48357a71-3891-4d31-bf73-8b7021b9759e)


**Dual Boot**
- Dual booting means having two operating systems run(like Windows and Linux) on one computer. When you turn on your computer, it lets you choose which one you want to use.
  
**ISO Files**
  - An ISO file (or ISO image) is a single file that contains the entire contents of a CD, DVD, or installation disc. It’s like a digital copy of a disc.
    
 **Bare Metal Installation**
- Bare metal installation refers to the process of installing an operating system (OS) directly onto a physical machine (a computer or server) without any existing OS or virtualization layer.
- Better performance: Since the OS runs directly on the hardware, it uses all of the machine's resources, making it faster and more efficient than a virtual machine.
- Full control: You get complete control over the system with no interference from virtualization layers.

**VM Ware**
-  It’s a virtualization software.
It can run multiple operating systems (OSes) on a single physical computer at the same time by creating virtual machines (VMs).

**Virtual Box**
- VirtualBox is free, open-source virtualization software from Oracle.It's generaly favoured for personal use,development,and testing.

  # Day-3
  **File and Directory permission**


  **Re-direction**
 - Redirection in Linux is about sending the input or output of commands somewhere else — instead of the default.
   - chmod (Change mode): It is used to change the access permissions of files and directories.
     
syntax -chmod [permission] [file]
for permission

./filename.sh for displaying
chmod +x filename.sh

+x enables executable file
chmod 444 filename.sh

444 enables a read only file
chmod 644 filename.sh

it enables permissions only to owner2.
![image](https://github.com/user-attachments/assets/d1c4d2f1-f5d8-48d9-b255-28595898b52a)

![image](https://github.com/user-attachments/assets/f213df28-85fe-45f7-88ec-d06007424265)

![image](https://github.com/user-attachments/assets/970929b9-9999-4313-a88a-15da16e63600)

**Shell Script Creation (.sh files)**

- Created basic shell scripts using nano

- Saved with .sh extension

- Made executable using chmod +X

- Ran scripts using: ./filename.sh

**Input/Output Redirection**

- Used redirection operators:

- > → write to a file

- >> → append to a file

- < → read input from file



# Redirection
- It means that sending  the input/output of command somewhere else.
- Normally, a command shows its result on the screen.
- With redirection, you can save that result to a file instead. 

#  Common Redirection Operators

| Operator | What it does                                       | Example                                     |                               
| -------- | -------------------------------------------------- | ------------------------------------------- | 
| `>`      | Redirect **output** to a file (overwrite the file) | `echo "Hello" > file.txt`                   |                               
| `>>`     | Redirect **output** to a file (append to the file) | `echo "Hi" >> file.txt`                     |                
| `<`      | Take **input** from a file                         | `sort < file.txt`                           |                                                              
| `&>`     | Redirect **output and errors** to a file           | `command &> alloutput.txt`                  |  


# Pipes
- A pipe is represented by the vertical bar character |. It takes the standard output (stdout) of the command on the left side of the pipe and passes it as standard input (stdin) to the command on the right.

  ![image](https://github.com/user-attachments/assets/307f2535-aade-4c0c-b77a-8e81a3399f3e)

![image](https://github.com/user-attachments/assets/622e1da2-eb5d-4cfe-923e-7f978b1e3141)

 # Example of comparing two numbers:
 ![image](https://github.com/user-attachments/assets/babc2e0a-665c-4914-adae-a82066b5ff92)

 ![image](https://github.com/user-attachments/assets/68d317ec-31aa-450b-9766-1c4918d4a612)
 
# Example of using variable:
![image](https://github.com/user-attachments/assets/98b10268-9981-465a-881b-dfbf98decf43)

![image](https://github.com/user-attachments/assets/c7de63a9-1c23-498a-a0e0-d6cd4baea78f)

# Eample of making a table of any number:

![image](https://github.com/user-attachments/assets/9ad59294-cf68-40dd-9964-06456f82eb83)


![image](https://github.com/user-attachments/assets/93ac166c-9c54-4309-9c5f-02914792cc10)

# Day-4
# Wildcard
- A wildcard is a symbol or character that can stand for one or more other characters.
  
For example:
- In file names: *.txt means “all files that end with .txt”.
- In programming: _ (underscore) might be used as a wildcard to match anything.

| Wildcard | Meaning                                        | Example          | Matches                           | Doesn’t Match    |
| -------- | ---------------------------------------------- | ---------------- | --------------------------------- | ---------------- |
| `*`      | Matches **zero or more characters**            | `*.log`          | `debug.log`, `error.log`          | `debug.log.bak`  |
| `?`      | Matches **one character**                      | `file?.txt`      | `file1.txt`, `fileA.txt`          | `file12.txt`     |
| `**`     | Matches directories **recursively**            | `docs/**`        | `docs/a.txt`, `docs/folder/b.txt` | `images/a.png`   |
| `/`      | Indicates **root directory** (in `.gitignore`) | `/config.yml`    | `config.yml` (in root)            | `sub/config.yml` |
| `!`      | **Negates** a pattern (un-ignore)              | `!important.log` | Keeps `important.log` tracked     | —                |
| `[...]`  | Character **range or set**                     | `file[0-9].txt`  | `file1.txt`, `file7.txt`          | `fileA.txt`      |
| `\`      | Escape special characters                      | `\!file.txt`     | Matches `!file.txt` literally     | —                |

# ASSIGNMENT: Escaping  Character
- Escaping characters are used in the Linux command line (like Bash) to prevent special characters from being interpreted by the shell.
- Escaping characters = Telling the shell:

  | **Escape Sequence** | **Character Represented** | **What it Does / Means**                    |
| ------------------- | ------------------------- | ------------------------------------------- |
| `\\`                | Backslash (`\`)           | Inserts a literal backslash                 |
| `\'`                | Single Quote (`'`)        | Inserts a single quote inside single quotes |
| `\"`                | Double Quote (`"`)        | Inserts a double quote inside double quotes |
| `\n`                | Newline                   | Moves the cursor to the next line           |
| `\t`                | Tab                       | Inserts a horizontal tab                    |

# HARDWARE 
- Hardware refers to the physical parts of any computer system — the components you can see and touch.

  | **Category**                 | **Examples**                                       | **Description**                                                    |
| ---------------------------- | -------------------------------------------------- | ------------------------------------------------------------------ |
| **1. Input Devices**         | Keyboard, Mouse, Scanner, Webcam, Microphone       | Allow users to enter data and commands into the computer.          |
| **2. Output Devices**        | Monitor, Printer, Speakers, Projector              | Display or produce results from processed data.                    |
| **3. Processing Devices**    | CPU (Processor), GPU (Graphics Card)               | Perform calculations and data processing.                          |
| **4. Storage Devices**       | HDD, SSD, USB Flash Drive, Optical Discs           | Store data permanently or temporarily.                             |
| **5. Memory Devices**        | RAM, Cache Memory                                  | Provide temporary storage for active data and processes.           |
| **6. Communication Devices** | Network Interface Card (NIC), Modem, Router        | Enable connection and communication with other computers/networks. |
| **7. Motherboard & Power**   | Motherboard, Power Supply Unit (PSU), CMOS Battery | Connect and power all components.                                  |
| **8. Peripheral Devices**    | Joystick, Gamepad, External Drives                 | Additional devices that expand functionality.                      |
| **9. Cooling & Enclosures**  | Cooling Fans, Heat Sink, Computer Case             | Manage heat and protect internal parts.                            |

# Main Components of CPU Cabinet

 | **Component**                   | **Description**                                                                                         |
| ------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Motherboard**                 | The main circuit board that holds the CPU, RAM, chipset, and provides slots/ports for other components. |
| **Processor (CPU)**             | The brain of the computer that performs calculations and instructions.                                  |
| **RAM (Memory)**                | Temporary memory used to store data that is actively used by the CPU.                                   |
| **Power Supply Unit (PSU)**     | Converts AC power to DC power and distributes it to all components.                                     |
| **Hard Disk Drive (HDD) / SSD** | Permanent storage for operating system, applications, and files.                                        |
| **Optical Drive (optional)**    | CD/DVD/Blu-ray drive (less common now).                                                                 |
| **Expansion Cards**             | Additional cards like graphics card (GPU), sound card, network card, etc.                               |
| **Cooling System**              | Includes CPU fan, case fans, and sometimes liquid cooling to manage heat.                               |
| **Cabinet Case**                | The enclosure that houses and protects all internal components.                                         |
| **Cables & Connectors**         | Wiring to connect power, data, and signal between components.                                           |


** Mother Board**
- It’s the main circuit board inside your computer.
- It connects all parts — CPU, RAM, storage, GPU, power supply, ports, etc.
- It provides slots and sockets for components to plug into.
- It carries the chipset, which controls data flow between CPU, RAM, and devices.
  

![image](https://github.com/user-attachments/assets/a6c9fbca-1c8c-4b06-bec4-1ba1535ff1e1)




# Difference Between RAM and Hard Disk:

|  **Feature**      |  **RAM**                         |  **Hard Disk (HDD/SSD)**                |
| ------------------- | ---------------------------------- | ----------------------------------------- |
| **Type of Memory**  | Temporary                          | Permanent                                 |
| **Data Retention**  | Data lost when PC is off           | Data stays when PC is off                 |
| **Speed**           | Very fast                          | Slower than RAM                           |
| **Capacity**        | Smaller (4GB–32GB)                 | Larger (500GB–2TB or more)                |
| **Main Use**        | Runs programs & active processes   | Stores OS, files, movies, games, software |
| **Effect on Speed** | Affects multitasking & performance | Affects storage capacity & file loading   |

# Difference Between RAM and Cache Memory:

|  **Feature**       |  **RAM (Random Access Memory)**         |  **Cache Memory**                                   |
| -------------------- | ----------------------------------------- | ---------------------------------------------------- |
| **Purpose**          | Holds data & programs currently in use    | Stores frequently used data/instructions for the CPU |
| **Location**         | External to CPU, on the motherboard       | Inside or very close to CPU chip (L1, L2, L3)        |
| **Speed**            | Very fast — but slower than cache         | Extremely fast — faster than RAM                     |
| **Size**             | Larger (4GB–64GB)                         | Very small (few KB to several MB)                    |
| **Cost per GB**      | Less expensive than cache                 | More expensive than RAM                              |
| **Access Frequency** | Accessed when CPU needs data not in cache | Accessed first by CPU for fastest data retrieval     |
| **Volatility**       | Volatile — data lost when power off       | Volatile — data lost when power off                  |


# ROM 
- ROM stands for Read-Only Memory. It is a type of non-volatile memory, which means the data stored in it is not lost when the computer is turned off.
  
**Key Features**
| Feature             | Details                                                            |
| ------------------- | ------------------------------------------------------------------ |
| **Non-volatile**    | Keeps its data even without power.                                 |
| **Read-only**       | Originally, you could only read data; now, we have updatable ROMs. |
| **Stores firmware** | Holds low-level software that directly controls hardware.          |

**Types of ROM**
- PROM (Programmable ROM) — Can be programmed once.

- EPROM (Erasable PROM) — Can be erased with UV light and reprogrammed.

- EEPROM (Electrically Erasable PROM) — Can be erased and updated electronically (used in modern BIOS as flash memory).

# Process of Booting 

| **Step** | **Hardware Involved**        | **What Happens**                                                                                   |
| -------- | ---------------------------- | -------------------------------------------------------------------------------------------------- |
| 1        | **Power Supply Unit (PSU)**  | Converts AC to DC power and supplies power to motherboard and all components.                      |
| 2        | **Motherboard & CPU**        | CPU starts working when it receives power; it begins executing instructions stored in ROM.         |
| 3        | **ROM (BIOS/UEFI Chip)**     | BIOS/UEFI firmware runs POST to check connected hardware (RAM, keyboard, drives, GPU, etc.).       |
| 4        | **RAM (Memory)**             | Once the BIOS checks the RAM, it loads the bootloader and OS kernel into RAM for fast access.      |
| 5        | **Storage Device (HDD/SSD)** | Contains the bootloader and operating system files. BIOS/UEFI reads these files to load them.      |
| 6        | **CPU + Motherboard Bus**    | CPU reads instructions via motherboard buses (data and address buses) and controls all operations. |
| 7        | **Peripheral Devices**       | Keyboard, mouse, display, and other input/output devices get initialized for user interaction.     |


# Day-5
# Computer Hardware and Troubleshooting 
# HDD
- Full form: Hard Disk Drive

- It’s a primary storage device that stores operating system files, software programs, personal files, documents, movies, music, games, and more.

- Unlike RAM (which loses data when the PC shuts down), an HDD keeps your data permanently until you delete it.

 # Key Features of HDD  

| Feature                              | Details                                                                                          |
| ------------------------------------ | ------------------------------------------------------------------------------------------------ |
| **Storage Capacity**             | Offers large storage space — from 500 GB to several TB (terabytes).                              |
| **Non-Volatile**                 | Data stays stored even when the PC is turned off — permanent storage.                            |
| **Magnetic Storage**             | Uses magnetic disks (platters) to store data by changing magnetic polarity.                      |
| **Moving Parts**                 | Contains spinning platters, read/write heads, actuator arms — works like a mini machine.         |
| **Data Access Speed**            | Slower read/write speed compared to SSDs — average 50–150 MB/s.                                  |
| **RPM (Revolutions Per Minute)** | Common speeds: 5400 RPM (slower, cooler, more energy efficient) or 7200 RPM (faster, more heat). |
| **Form Factor**                  | Desktop: 3.5-inch size; Laptop: 2.5-inch size.                                                   |
| **Interface**                    | Connects via SATA (Serial ATA) or older IDE — also has a power connector.                        |
| **Cost Effective**               | Cheaper per gigabyte than SSDs — best for large data storage.                                    |
| **Lifespan**                      | Can last 3–5+ years with careful handling — sensitive to drops and shocks due to moving parts.   |

# Types of HDD 

| Type                      | Description                                                                                                             | Common Use                                                     |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **Desktop HDD**       | Standard 3.5-inch drives, larger size, higher capacity (500 GB–10 TB).                                                  | Desktop PCs, gaming PCs, home storage.                         |
| **Laptop HDD**        | Smaller 2.5-inch drives, designed to fit thin laptops, usually less capacity (500 GB–2 TB).                             | Laptops, notebooks.                                            |
| **External HDD**      | Portable drives enclosed in a case with USB, eSATA, or Thunderbolt interface.                                           | Backups, file transfer, portable storage.                      |
| **Enterprise HDD**    | High-performance, heavy-duty drives for servers & data centers; built for 24/7 operation, higher reliability.           | Servers, NAS (Network Attached Storage), large storage arrays. |
| **NAS HDD**           | Specially designed for **Network Attached Storage**, supports multiple drives working together, optimized for 24/7 use. | Home/Office network storage.                                   |

# PROBLEMS: When your PC is going slow 

- A slow PC can be caused by many reasons, but here are common causes related to HDD and other parts:

**Hard Disk Drive (HDD) Issues**
**Fragmentation**

- On older HDDs (not SSDs), files get scattered (fragmented) over time. This slows down read/write speed.

- Solution: Run Disk Defragmenter (Windows: Defragment and Optimize Drives).

**Almost Full HDD**

- If your HDD is more than 80–90% full, your PC slows down — less space for temporary files.

- Solution: Delete unwanted files, empty Recycle Bin, move large files to an external drive.

**Bad Sectors**

- Over time, an old HDD may develop bad sectors that slow down data access.

- Solution: Run chkdsk in Windows to scan & fix disk errors.

**Old & Failing HDD**

- HDDs with moving parts wear out — they may get slower, make clicking sounds, or freeze.

- Solution: Backup your data ASAP and consider replacing the HDD.

**Software & System Issues**

**Too Many Startup Programs**

- Many apps auto-start and slow down booting.

- Solution: Disable unnecessary startup programs (Task Manager → Startup tab).

**Heavy Apps Running**

- Running many heavy apps at once uses too much RAM & HDD access.

- Solution: Close unused apps/tabs.

**Malware or Virus**

- Malware eats up system resources.

- Solution: Run antivirus scan.

**Outdated OS/Drivers**

- Old drivers or updates missing can slow performance.

- Solution: Keep Windows & drivers updated.

**Hardware Limits**

**Low RAM**

- Not enough RAM? System uses HDD as virtual memory — much slower.

- Solution: Add more RAM if possible.

**Using HDD instead of SSD**

- HDDs are much slower than SSDs — booting & loading takes longer.

- Solution: Upgrade to an SSD for faster boot and programs.

# What you can do right now

- Disk Cleanup	Use Disk Cleanup tool to delete temp & junk files.
- Defragment	Defrag your HDD if it’s not an SSD.
- Scan for Malware	Use Windows Defender or trusted antivirus.
- Check Startup Apps	Disable unnecessary ones.
- Upgrade	If possible, upgrade to SSD & add more RAM.

# Printer Issues & Solutions 


| **Issue**                   | **Possible Causes**                                                               | **Solutions**                                                                                     |
| --------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Printer not printing**    | Printer offline, cable loose, wrong printer selected, paper jam, out of ink/toner | Check cables/power, select correct printer, clear jams, check ink/toner, restart printer & PC     |
| **Paper jam**               | Torn or wrong-size paper, overloaded tray, dirty rollers                          | Remove jam carefully, use good paper, don’t overload, clean rollers                               |
| **Poor print quality**      | Low ink/toner, clogged print head, wrong paper type, low-quality settings         | Refill/replace ink/toner, clean print heads, align heads, use correct paper, adjust print quality |
| **Printing too slow**       | High-resolution mode, large file, weak Wi-Fi                                      | Lower print resolution for drafts, connect by USB, move printer closer to Wi-Fi                   |
| **Printer shows ‘Offline’** | Lost connection, printer in sleep mode, wrong port/driver                         | Check Wi-Fi/USB, restart printer & PC, reinstall driver, set printer to ‘Online’                  |
| **Driver problems**         | Corrupt/missing drivers, OS update issues                                         | Download latest drivers from official site, uninstall/reinstall drivers, restart PC               |
| **Ink dries up (inkjet)**   | Printer unused for long time                                                      | Print a test page regularly, run cleaning cycle                                                   |
| **Strange noises**          | Hardware problem, stuck debris                                                    | Open printer, check for debris, call technician if needed                                         |

# BSOD 
- BSOD stands for Blue Screen of Death.
- It’s an error screen displayed by Windows when your computer suddenly crashes due to a serious system error.

# Why does BSOD happen?

**Common causes include:**
- Hardware failure — faulty RAM, hard disk, motherboard, overheating.
- Driver problems — outdated or corrupted device drivers.
- Corrupted system files — missing or damaged Windows files.
- Software conflicts — badly written programs or malware.
- Overclocking — pushing hardware beyond safe limits.

# BIOS/UEFI Settings

| Feature          | **BIOS**                  | **UEFI**                               |
| ---------------- | ------------------------- | -------------------------------------- |
| **Full Form**    | Basic Input/Output System | Unified Extensible Firmware Interface  |
| **Interface**    | Text-based, keyboard only | Graphical, supports mouse              |
| **Disk Support** | MBR partition (≤ 2 TB)    | GPT partition (> 2 TB)                 |
| **Security**     | Basic password            | Secure Boot, better malware protection |
| **Drivers**      | Stored in BIOS chip       | Can load drivers from a storage device |
| **Performance**  | Slower boot               | Faster boot and resume                 |
| **Updates**      | Manual, simple            | Easier, some auto-update options       |
| **Common Use**   | Older PCs                 | Modern PCs & laptops                   |


# What is POST (Power-On Self-Test)
- It’s a diagnostic process your computer does automatically every time you power it on.
- When you press the power button, POST checks if your hardware is working properly before loading the operating system.

**It checks:**

- CPU (Processor)
- RAM (Memory)
- Keyboard & basic input devices
- Video card
- Basic motherboard functions
- Storage devices (HDD/SSD)

