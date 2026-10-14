**Date:** 2026-10-14
**Difficulty:** Easy
**Solved without hints:** Yes

## Task

Log in as bandit0, find the password for bandit1.

## Approach

1. SSH into the server as bandit0
2. The hint said "The password is in the file readme"
3. Read the file

## command

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
cat readme
   
### password
bandit0

## What i learnt

cat to read a file
