### Simple Shell

A UNIX command interpreter built from scratch, written in C without using any of the standard library functions. By [Lee Gaines](https://github.com/eightlimbed) and [Liz Magalindan](https://github.com/magezil/).

### Compilation

```
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```

### Usage

#### Interactive mode
```
$ ./hsh
hsh$ /bin/ls
hsh main.c shell.c
hsh$
hsh$ exit
$ 
```

### Non-interactive mode
```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c
$
```
