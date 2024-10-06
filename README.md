# HELLO HACKERS 
## Intro to Commands

For the first module we invoke our first command i.e., whoami and hit enter which simply prints the username (hacker).
```bash
hacker@hello~intro-to-commands:~$ whoami
hacker
hacker@hello~intro-to-commands:~$ 
```
Now to get the flag we type hello and hit enter. 
```bash
hacker@hello~intro-to-commands:~$ hello
Success! Here is your flag:
pwn.college{8EOWq-VFwRaD40XxLOfAPiQwH68.ddjNyUDL1IDM1czW}
hacker@hello~intro-to-commands:~$ 
```

## Intro to arguments 

In this case, "hello" is the command (term that prints the argument) and "hackers" is the argument. Hence it will give the flag. 
```bash
hacker@hello~intro-to-arguments:~$ hello hackers
Success! Here is your flag:
pwn.college{UScXQ15sPAaSJ91vztdBe0f5ulX.dhjNyUDL1IDM1czW}
hacker@hello~intro-to-arguments:~$
```

# PONDERING PATHS
## The Root

So the filesystem starts at /. Under that, there are a whole mess of other directories, configuration files, programs, etc. In this case, they have included a program called "pwn" under /. So to invoke the program and capture the flag we type "/pwn" (this is called the path) and hit enter.
```bash
hacker@paths~the-root:~$ /pwn
BOOM!!!
Here is your flag:
pwn.college{kUwSxM4oMzlh2VVQUw9W8CY5PF5.dhzN5QDL1IDM1czW}
hacker@paths~the-root:~$
```

## Program and absolute paths 



