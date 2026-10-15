*date 15/10/2026*
**difficulty level  easy**


**Task**
To find the password for the bandit 3 stored in a file called 
--spaces in this filename--
located in the home directory

**Approach**

- listed the files with ls to find the file  *--spaces in this filename--*
- read the file with cat ./

**Commands** 
- ls 
-  cat "./--spaces in this filename--"
 **password**
 7ZZ2LFrykP2zEyvBl4m3clcL7tGYJPME for bandit 3

**learnt**

The key thing: **the filename starts with `--`**, so the shell/command interprets it as a flag, not a filename.

The fix is the **`./` prefix** — it tells `cat` "this is a file path, not an option":

