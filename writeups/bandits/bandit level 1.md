**Date:** 2026-10-14 
**Difficulty:** Easy 
**Solved without hints:** Yes

## Task
Find the password for bandit2. The hint said "The password for the next level is stored in a file called '-' in the home directory."

## Approach

   1 Listed files with `ls` — saw a file named `-`
2. Tried `cd ./-` — it's a file, not a folder 
3. Read it with `cat` ./

## commands
ls
 cat ./-
## password found

bandit 2 PK8fYLZg2hnHSz83plBL1iEPKdD3QToB

## What I Learned

- Files can be named `-` (which confuses commands that expect flags)
    
- Use `./-` to tell the command it's a file, not a flag
    
- `cat` reads files, `cd` is for directories only


