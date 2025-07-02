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




  



