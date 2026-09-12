# 19CS416-CS-Ex-3-Linux-Commands
```
NAME:V.Lakshita Rai
REG NO: 212225220054
```
## AIM:
To study the execution of various Linux operating system commands.

## LINUX:
**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
<img width="568" height="267" alt="421769167-55aac873-2a3e-4b66-b57b-c2e740fe2628" src="https://github.com/user-attachments/assets/9f3e0df0-1a45-427e-92ef-7d9eec20fe94" />


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
<img width="550" height="44" alt="421769220-fe2482fb-ea23-4e2d-8d34-abfcb2b2f8b4" src="https://github.com/user-attachments/assets/6127fc63-86d9-4d39-8b03-e0dd28210b53" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
<img width="543" height="26" alt="421769313-7742bba7-0054-4cc1-8a65-c36065f8b03e" src="https://github.com/user-attachments/assets/9ba47463-4a0f-41ba-9b2a-c16e89bce766" />

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
<img width="543" height="26" alt="421769415-80e32a11-9a47-410f-932a-13585c106611" src="https://github.com/user-attachments/assets/4bd2bcc3-1c58-44c7-b326-7d76cf57bdf3" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
<img width="543" height="26" alt="421769478-53a8c7bd-c19b-4d19-bb50-316b4c5c35b3" src="https://github.com/user-attachments/assets/7d787f33-d369-42fd-9c77-f1575bb4e526" />

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="557" height="51" alt="421769934-0b7d6a58-45d3-4536-88c1-662058ef68b4" src="https://github.com/user-attachments/assets/8e63221d-6954-44fc-8a94-950444ae8ebb" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
<img width="672" height="143" alt="421770236-124aed10-fc05-4637-bfb4-ba713e3f9030" src="https://github.com/user-attachments/assets/2884bedd-0bfc-4a7a-a660-38a84f57d1d3" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
<img width="676" height="27" alt="421770373-b6ec2111-2eb3-4613-860e-a0147a2fd31f" src="https://github.com/user-attachments/assets/e9eaa8c8-5e9e-46c1-9a2e-0e012215526b" />

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
<img width="676" height="27" alt="421770626-2dab84e7-7ae0-4f51-bf46-e32a4d0a6a52" src="https://github.com/user-attachments/assets/be3c44c5-20dd-4c85-b812-142781737af2" />

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
<img width="676" height="27" alt="421771357-c37e9e11-5615-4702-b081-447217695894" src="https://github.com/user-attachments/assets/511d5e15-5d46-4179-a110-548827a9aeaa" />

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
<img width="676" height="27" alt="421771439-e3d3b731-5b21-44c8-8ffb-e5c40bafd4bc" src="https://github.com/user-attachments/assets/a0a36c73-a87f-4de6-9295-90de78fd5324" />

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="730" height="63" alt="421771544-19f2cc01-2bbf-4773-89cb-072fd16828e2" src="https://github.com/user-attachments/assets/225b8745-a19b-4627-8400-a9d6e973110e" />

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
<img width="466" height="58" alt="421771639-735d463e-d56d-4047-b84b-63f3b7e4629d" src="https://github.com/user-attachments/assets/34f6bb6b-47e8-4810-8d54-43e2dcaee2cb" />

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
<img width="1214" height="44" alt="421772833-8bdd8a8f-d70e-4bbc-95f8-db26b1271772" src="https://github.com/user-attachments/assets/15aba7da-d00e-40bb-baa4-092a2c0e999d" />

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
<img width="571" height="76" alt="421777100-6e6c1534-72bb-44c2-882e-54fb50f4dba2" src="https://github.com/user-attachments/assets/3bfec02d-aaa3-4711-b8d4-c944baa4a5e9" />

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
<img width="570" height="226" alt="421778291-0be5c779-3c36-484c-b9d6-c03928d535a7" src="https://github.com/user-attachments/assets/cd8afc1d-79c4-42a2-b5c0-1d46f78b3e7b" />

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
<img width="601" height="24" alt="421779596-b496cf9a-d1b0-4026-9d95-88be00f3c835" src="https://github.com/user-attachments/assets/178e274f-077d-4f02-b17a-db692f5c2d82" />

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
<img width="603" height="39" alt="421780682-cd5fa012-5f83-4539-8b36-2da6f1cdfba7" src="https://github.com/user-attachments/assets/f482117b-1997-494c-a789-9cd972fcfa5b" />

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
<img width="631" height="23" alt="421793473-8814f5ae-23ee-411f-8383-0ac2a175b874" src="https://github.com/user-attachments/assets/cb9cb50b-5116-43e5-b8db-f2d1ac1b872b" />

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
<img width="634" height="40" alt="421792556-ce4cfd2d-7f5a-421f-be60-af885b574fa6" src="https://github.com/user-attachments/assets/939c99c6-2c18-42d3-8863-017446c3abb9" />

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
<img width="693" height="491" alt="421790753-4ddf3532-2c94-48ea-866d-ec8c013b942e" src="https://github.com/user-attachments/assets/7f8607c7-2b10-4dff-b1d9-ad2b9d738b2b" />

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
<img width="698" height="24" alt="421789785-e24619be-b7c4-4605-96f3-33394061d0ec" src="https://github.com/user-attachments/assets/b273da03-7fbd-4e0b-9d9f-fc20c65389c8" />

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
<img width="603" height="39" alt="421782592-5e639104-5660-4d9c-9862-bf82c039727f" src="https://github.com/user-attachments/assets/0c6cd609-c6c9-4fad-96c5-187b8f79d509" />

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
<img width="589" height="22" alt="421783462-1e9562c0-7e52-4675-a158-ed6f8fed1166" src="https://github.com/user-attachments/assets/879ecf47-2c0c-4ebb-9229-2ac8d157accb" />

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
<img width="594" height="256" alt="421783931-abf9b671-77b6-4400-b053-1de460b713b9" src="https://github.com/user-attachments/assets/e9ccd878-ef33-4a64-8016-5ed1a68dc720" />

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
<img width="570" height="169" alt="421784292-5b26c9c0-e82c-4fab-aede-831b2c7016c7" src="https://github.com/user-attachments/assets/335e77cf-140c-4817-aa0c-97e7f1b2fc58" />

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
<img width="570" height="169" alt="421784565-51d6674b-8d46-4ab5-a05e-612a441d08d8" src="https://github.com/user-attachments/assets/4a31790b-7dd7-4b03-b3e4-1dae8b9bb051" />

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
<img width="731" height="87" alt="421786979-97d31451-b572-4400-96a9-e7f3e4fe8fa1" src="https://github.com/user-attachments/assets/6188403d-5de6-411a-b188-74885531f2d8" />

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
<img width="734" height="209" alt="421787106-6b69d9a7-5810-4c0d-add8-31e0ed490320" src="https://github.com/user-attachments/assets/f0d8f0ff-0264-41a1-af46-d00745b7e86f" />

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
<img width="707" height="47" alt="421789145-76490a0c-f4c2-40a2-996f-87b3d52bc6db" src="https://github.com/user-attachments/assets/ce1a24bb-6f6f-4257-8eec-2710d584ad0e" />


## Result
