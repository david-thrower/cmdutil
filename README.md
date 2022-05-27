# cmdutil
A python utility for (sanely an non-annoyingly) running shell commands within a python script. Simply pass a shell command as an argument. It will return the stdout as a string and will raise an exception if the process returns a non-zero status.

Use:

```
from cmdutil.cmdutil import run_command

cmd = "tar -czvf archive.tar.gz archive"
console_output = run_command(cmd)

```
