
## `awk`

### Example:

Imagine you have a file named report.txt with the following content:
```bash
ID  Name    Age Location
101 John    34  New_York
102 Jane    29  Los_Angeles
103 Peter   45  Chicago
```

If you run the command `awk -F" " '{print $4}' report.txt`, the output would be:

```bash
Location
New_York
Los_Angeles
Chicago
```

---


The command `awk -F" " '{print $4}'` prints the fourth column of data

`F`: field separator

`$2`: Represents the second field, and so on.

`$4`: Represents the fourth field, and so on.


---
