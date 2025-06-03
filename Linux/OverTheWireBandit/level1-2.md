## Bandit level 1-2

**Level Goal**
The password for the next level is stored in a file called `-` located in the home directory.  

**Commands used**
- 'ssh'
- 'ls'
- 'cat'
- 'exit'

**Solution**
1. Connect to the Bandit server as bandit1 using the password you found in the previous level:
- ' ssh -p 2220 bandit1@bandit.labs.overthewire.org '
2. List the files in the home directory to see what’s available:
ls
- You'll see a file named ' - '
3. Read the contents of the file named ' - '
cat ./-
- This command tells the shell to read the file named - in the current directory.
- You’ll see the password for Level 2. Note it down!
4. Exit the session.
exit