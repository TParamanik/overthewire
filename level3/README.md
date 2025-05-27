Start a new connection with the command

```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
```

If we run the command "ls" it doesnot show any files or folders, which means they are hidden.
So to view the hidden files we need to run the command "ls -a". We will find 2 hidden folders and a file.
Read the content of the file.

```bash
cat "...Hiding-From-You"
```

OR

```bash
cat ./...Hiding-From-You
```

Then we will get the password: "2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ"
