## Bandit Level 1-2

**Level goal:**

The password for the next level is stored in a file called 'readme', located in the home directory.
Use this password to log into 'bandit1' using SSH (on port 2220) and continue the game.

**Commands Used:**

- ssh
- ls
- cat

**Solution:**

1. List the files in the home directory using:
ls
- you should see a file names 'readme'

2. Read the contents of the 'readme' file to get the password for the next level:
cat readme
- This will display the password for level 1. Note it down!

3. Exit the session.
exit
- This returns you to your local terminal so you can log into Level 1 using the new password.
