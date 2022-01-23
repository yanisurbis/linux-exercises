```
2

The table below shows the section numbers of the manual followed by the types of pages they contain.

       1   Executable programs or shell commands
       2   System calls (functions provided by the kernel)
       3   Library calls (functions within program libraries)
       4   Special files (usually found in /dev)
       5   File formats and conventions, e.g. /etc/passwd
       6   Games
       7   Miscellaneous (including macro packages and conventions), e.g. man(7), groff(7)
       8   System administration commands (usually only for root)

---

3

man -k printf
           Search  the  short  descriptions  and manual page names for the keyword printf as regular expression.  Print out any
           matches.  Equivalent to apropos printf.

---

4

The command ls lists the contents of the current directory—it tells you what files you have.  With a -l option it  gives
       a  long  listing,  that  includes  the  owner and size and date of the file, and the permissions people have for reading
       and/or changing the file.  For example, the file "tel" here is 37 bytes long, owned by aeb and the owner  can  read  and
       write it, others can only read it.  Owner and permissions can be changed by the commands chown and chmod.

---

5

ls -laht

---

6

date +"%Y-%m-%dT%H:%M:%S%:z"

```

