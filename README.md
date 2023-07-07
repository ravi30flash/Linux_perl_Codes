# linux

> linux is kernel not a operating system

## topics to read about in linux
* File and directory management
* User & Group management
* Permission management
* service management
* Network management
* Security management
* Bash Scripting
* filtering

<details>
<summary>File and Directory Management </summary>

> in linux everything is a file  
> directory are the file containers

### How to create a file
* `touch [file-name]`
* `vi [file-name]`

### How to create a directory
* `mkdir [dir-name]`

### How to rename a file or directory
* `mv [old_name] [new_name]`

### How to move a file or directory
* `mv [old_path] [new_path]`

### How to copy a file or directory
* `cp [old_path] [new_path]`

### How to read a file
* `cat [file-name]`

### How to delete a file or directory
```bash
# to delete a directory
rm -rd [dir-name] 
# to delete a file
rm [file-name]
```  
</details>


<details>
<summary> User & Group Management </summary>

### How to create a user
* `useradd [options] [user-name]`
### How to delete a user
* `userdel [options] [user-name]`
### How to create a group
* `groupadd [options] [group-name]`
### How to create a group
* `groupdel [options] [group-name]`

### How to change group for a given user
* `usermod -g [group-name]`



</details>