# gueg
gueg(Great User Email Generator) is a python utility for generating user and email address worlists.



## Use
Use case:
Say you found an email address `jdoe@example.local` for the user John Doe, you know that the pattern is First Name Letter + Surname + @example.local. The command used to generate  a wordlist with a similar pattern would be:
```
python3 gueg.py -l names.txt 1 '' -l surnames.txt 99 '' -a @example.net
```
The wordlist generated would be something like:
```
nleon@example.net
trivera@example.net
bmendoza@example.net
```
