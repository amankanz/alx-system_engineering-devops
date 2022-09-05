#!/bin/bash
echo "Hello, World"  prints “Hello, World”, followed by a new line to the standard output.
cat etc/paswd Display the content of the /etc/passwd file
cat /etc/passwd /etc/hosts  Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd  Display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd  Display the first 10 lines of /etc/passwd
gre "root" /etc/passwd  Display lines containing the pattern “root” from the file /etc/passwd

