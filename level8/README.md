To solve this we need to find a line which occurs only once.
We need command:

```bash
sort data.txt | uniq -u
```

First sort will organize all lines so that duplicates are next to each other
uniq -u: removes repetition and displays the lines exactly once
