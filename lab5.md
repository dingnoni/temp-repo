# lecture_note_5.md
---

## >
redirect output using it. 
after a command to create and save the output file

## >>
appends output to an extising file
or create and write to a new file if it doesn't exist.

## <
redirect input using it.
can mix < and > together in a single line

## cat
display the content of a text file

## |
output of previous command to input of next command

## echo
print out the text
echo * -> all file in directory 
echo ~ -> user home directory

``` sh
Tip 💡
blackslash can be used to ignore line change in command ("enter"), to enter a long command in multiple lines
```

## permissions
Linux is multi-user-system

File type:
/ - indicates regular file
/ d indicates directory

## chomod

changing permission
owner/group/others -rwx/rwx/rwx 
r = Read, w = Write, x = Execute

```
777: (rwxrwxrwx) No restrictions on permissions. Anybody may do anything.
775: (rwxr-xr-x) Owner read, write and execute. All others read and execute the file.
700: (rwx------) Owner read, write and execute. Nobody else has any rights.
656: (rw-rw-rw-) All user may read and write the file.
644: (rw-r--r--) The owner may read and write file, while all others may only read the file.
600: (rw-------) The owner may read and write a file. All others have no rights.
```

## sudo
Superuser has all system administation authority.
sudo some_command

## Shell Script
ex) nano myscript.sh

``` sh
Tip 💡
type "history" to see previous command history.
Or, save it to a text file
```

