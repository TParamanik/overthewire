Start a new connection with ssh and bandit4(for new level)@host -p port. Refer to previous level.
Search for files or folders. Change the directory into the folder. We will find so many files. We can manually check for the content of each files. But to save time, we can use the command:

```bash
grep -I -r . .
```

-I will ignore the garbage or binary files
-r will recursively search through directories
first'.' is treated as a pattern, "match any single character"
second'.' is to search through all the directories starting from the present

We will find the password in file7: "4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw"
