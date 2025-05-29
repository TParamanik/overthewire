Repeat the previous steps to establish a new connection and use level4 password to login.
Then we can find that the folders have many folders and files in it with human readable data, so it is difficult to find the key. I observed that keys are of 32 characters, so I started searching for that using the command.

```bash
grep -rE '^[a-zA-Z0-9]{32}$' .
```

-r recursive
E expression
It will search for character length 32 which has uppercase or lowercase letters or digits without any gaps.

The password is in maybehere07 > file2: "HWasnPhtq9AVKe0dmk45nxy20cvUa6EG"
