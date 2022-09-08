0. ls="rm *": create an alias that execute rm * for ls.
1. echo hello $USER: a script to print hello user.
2. PATH=PATH:/action:  add /actionto the path. /action should be the last directory the shell look into for a program.
3. echo $PATH | tr ':' '\n' | wc -l: count the number of directories in the path
4. printenv: script to print the global variables.
5. set: list local variables.
