# Command Line Fundamentals

The **Command Line Interface (CLI)** offers:  
- Efficiency  
- Lower resource usage  
- Precise system control  

Windows → **cmd.exe** (Command Prompt)  
Advanced Windows → **PowerShell**  
Linux → **Bash** (Bourne Again Shell)  

---

## 1. Windows Command Prompt (cmd.exe)

### System Information
- `ver` → Displays OS version.  
- `systeminfo` → Shows detailed system info.  

<img src="https://github.com/user-attachments/assets/30e85dc4-b657-401e-a072-c21ccd3cd4c4" width="600" />

### Networking
- `netstat` → Shows port connections.  
- `ipconfig` → Displays IP address/configuration.  

<img src="https://github.com/user-attachments/assets/9753b0b8-c56b-4e47-8a13-f573837798cb" width="600" />

### File & Directory Management
- `cd` → Change directory.  
- `mkdir` → Make directory.  
- `rmdir` → Remove directory.  
- `move` → Move files.  
- `copy` → Copy files.  
- `del` → Delete files.  

<img src="https://github.com/user-attachments/assets/e6d95353-b456-4841-bcd0-a526245aa26f" width="600" />  
<img src="https://github.com/user-attachments/assets/a935cb68-dc35-4fbb-a36f-80d813331236" width="600" />

### Process Management
- `tasklist` → List running processes.  
- `taskkill /PID <id>` → Kill process by PID.  

### Shutdown Commands
- `shutdown /r` → Restart.  
- `shutdown /a` → Abort shutdown.  

---

## 2. PowerShell (Windows)

### Core Features
- Works with **objects**, retaining properties & methods (more powerful than CMD).  
- **Syntax:** Verb-Noun format.  

Examples:  
- `Get-Command` → List commands.  
- `Get-Help <command>` → Show help & parameters.  
- `Get-Help New-LocalUser -Examples` → Usage examples.  

<img src="https://github.com/user-attachments/assets/0a09befe-60ff-4957-8092-7b8a1f47a212" width="600" />

### Common Commands
- `Get-Command -Name Remove*` → Filter commands by name.  
- `Get-Content` → Display file contents (like `type`).  
- `Get-ChildItem` → List files/directories (like `ls`).  
- `Get-LocalUser` → List all local user accounts.  

<img src="https://github.com/user-attachments/assets/4a72bbcd-629a-4104-a9ed-e368c1add53d" width="600" />

### Remote Management
- `Invoke-Command` → Run commands on remote systems.  

---

## 3. Linux / Bash

### Basics
- **Bash** = Bourne Again Shell (default on Linux).  
- `ls` → List directory contents.  
- `grep` → Search for keywords in files.  
- `history` → Show all executed commands.  

<img src="https://github.com/user-attachments/assets/fa8cab50-f08b-4ed0-8ad6-cd6a6539bc4f" width="600" />

### Scripting
- **First Script** → Create `.sh` file and run.  
- **Loops Example**:  
  ```bash
  for i in {1..5}; do
      echo "Number $i"
  done















