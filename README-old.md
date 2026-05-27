# dialog
Small tool to use windows in a shell script

With Dialog it is possible to create shell scripts using windowing system.
For example:
```
#!/bin/bash
if dialog --yesno Do you want to display the time \? ; then
 date
else
 echo sorry
fi
```
