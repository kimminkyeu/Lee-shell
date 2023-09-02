## The objective of this project is to create a simple shell.

![Untitled](image/Untitled.png)

## Compile & Run
this project is for Linux, MacOS. (Windows is currently not supported)

```bash
# 1) get source from repo
git clone https://github.com/kimminkyeu/Lee-shell 

# 2) build with Makefile
cd ./Lee-shell
make

#3) run shell program
./lesh   
```

## Available command list
- `|` pipe, redirection `>>` `>` `<`
- `<<` read input from the current source until a line containing only the delimiter is seen.
- `&&`, `||` with `()` parenthesis for priorities
- `echo` with option -n
- `cd` with only a relative or absolute path
- `pwd` with no options
- `export` with no options
- `unset` with no options
- `env` with no options or arguments
- `exit` with no options
- Environment variables ( `$` followed by characters) expand to their values.
- `’` inhibit all interpretation of a sequence of characters.
- `"` inhibit all interpretation of a sequence of characters except for `$`.

### Example 
![image](https://github.com/kimminkyeu/Lee-shell/assets/60287070/4a3755c1-ab66-4e54-a1bf-dcf74a6ea407)

## Have fun!
