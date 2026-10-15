Task
The password for the next level is stored in a file somewhere under the **inhere** directory and has all of the following properties:

- human-readable
- 1033 bytes in size
- not executable

**approach**
ls
cd read the **folder**
list files in the folder
find the file with the above properties by  find . -type f -size 1033c ! -perm -u+x

**commands**
find . -type f -size 1033c ! -perm -u+x
 **lesson** 
1. **`find`** — searching files recursively with multiple filters in one command
    
2. **`-size 1033c`** — the `c` suffix means _bytes_ (without it, `find` assumes 512-byte blocks)
    
3. **`!` for negation** — `! -perm -u+x` means "NOT executable"
    
4. **Combining conditions** — you can chain multiple `-type`, `-size`, `-perm` flags together
    
5. **`-exec` / piping** — you can pipe `find` output into `file` or `cat`, or use `$(...)` substitution
**password** 

pXa26xhMWaC2SvDotA4r9EgZkulOeSBW