# The default PowerShell prompt is boring

The default PowerShell prompt looks like this:
```
PS C:\Users\Adam>
```

Better than nothing, but not much.

## TimeHostUserLast2Cwd

Instead, let's have the prompt include:
* 24-hour time when the prompt was generated
* user (including host/domain)
* the path qualifier (e.g. drive letter)
* the lowest two elements of the current working directory
```
[02:03][ICEBERG\Adam][C:|Adam\PowerShell]> pwd

Path
----
C:\Users\Adam\PowerShell
```
