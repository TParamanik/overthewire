Repeat the steps to establish connection and use the password found in previous level.
Now this level requires some properties:

> owned by user bandit7
> owned by group bandit6
> 33 bytes in size

So I used this command:

```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

find /: Starts searching from the root directory /—i.e., the entire server filesystem.

-type f: Limits the search to regular files (ignores directories, links, devices).

-user bandit7: Finds files owned by the user named bandit7.

-group bandit6: Finds files owned by the group named bandit6.

-size 33c: Finds files that are exactly 33 bytes in size (c stands for bytes).

2>/dev/null: Redirects error messages (like permission denied) to /dev/null (i.e., hides them) so the output is cleaner.

The password was in /var/lib/dpkg/info/bandit7.password
Read the file using "cat"

Password is : "morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj"
