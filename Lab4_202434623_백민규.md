# 4주차 오픈소스 정리
---
## ***Linux***
Popular Open-Source, Unix-like operating systems and kernals.
### *Kernel and Shell*
Kernel: Core of OS, controls and communicates with hardware resource.

Shell: Interface, allows users to communicate with kernel.
- CLI: Command Line Interface, Using keyboards to write, fast, for developers.
- GUI: Graphical User Interface, Mostly Using Mouse, slow, for daliy users.
---
#### *Shell commands*
- pwd: Show the current path in a hierarchical directory.
- cd: Change directory.
- ls: List files and dirctories.
- clear: Clear all contents in the command visually.
- cp: Copy files and directories.
- mv: Move files and directories or rename them.
- rm: Delete files and directories permantely and irreversibly.
- mkdir: Make a new directory.
---
##### *ls*
- ls /bin: List the files in the /bin directory.
- ls -l: List the files in long format.
- ls -l /etc /bin: List the files in the /bin directory and the /etc directory in long format.
- ls -lh: List the files in long format but size in units.
- ls -la ..: List all files in long format.
  ###### *Long Format*
  In order of File Permissions\-Owner\-Gruop\-Size\-Modification Time\-File Name.
---
##### *Cp*
- cp file1 file2: Copies the contents of file1 into file2. If file2 does not exist, it is   created. Otherwise, it ocerwritten with the contents of file1.
- cp file1 dir1: Copy the contents of file1 inside of dir1.
- cp -r dir1 dir2: Copy the contents of dir1. If dir2 does not exist, it is created.     Otherwise, it creates dir1 within dir2.
---
##### *Mv*
- mv file1 file2: If file2 does not exist, file1 is renamed as file2. If file2 exists, its contents are replaced with the contents of file1.
- mv file1 file2 dir1: The files file1 and file2 are moved to dir1. If dir1 does not exist, mv will exit with an error.
- mv dir1 dir2: If dir2 does not exist, dir1 is renamed as dir2. If dir2 exists, dir1 is moved within dir2.
---
##### *Wildcards*
- \*\: All filenames.
- g\*\: All filenames that begin with the character \"g\".
- b\*\.txt: All filenames that begin with the character \"b\" and end with the character \".txt\".
- Data???: Any filename that begins with the characters \"Data\" followed by exactly 3 more characters.
---
##### *Tips*
- \"Tab\": Autocompletion.
- \"up arrow\": Past commands.
- help
- man
