## Hi there！ It's Bruce
## Here is my Lab report for week 5：

# More Less Commands!
- Here are some 'less' commands that we could use to make our life easier.

```
  - less -N filename
```

  - ![Image](4.1.png)

  - -N command helped to shows line numbers.


```
  - less -X filename
```
  - ![Image](4.2.png)
  - ![Image](4.3.png)

  - By default, when less exits, the file contents will be cleared from the screen.
  - The -X command helps to leave file contents on screen

```
  - less +F filename
```
  - ![Image](4.4.png)
  - ![Image](4.5.png)
  
  - The +F option tells less to watch the file contents for changes. This is useful when opening log files.

# More Find Commands!

```
  find -D help
```
  - This command is very useful to diagnose problems with why find is not doing what you want.
  - ![Image](4.6.png)

```
  find . -type f
```
  - This command helps to find type f of files in the provided directory
  - f means normal files like .txt
  - It works like this
  - ![Image](4.7.png)

```
  find . -type f
```
  - This command helps to find type f of files in the provided directory
  - It works like this
  - ![Image](4.8.png)

# More Greb Commands!

```
  grep -i "String" file
```
  - This command helps to ignore uppercase vs. lowercase; it's helpful when you do not want to care about lower and upper cases.
  - It works like this
  - ![Image](4.9.png)

  - You see the american is not uppercased but there are still 81 results
  - and without -i it matches 0

```
  grep -v "String" file
```
  - This command helps to searched the reservsed, inverted match of results.
  - ![Image](4.10.png)

  - Since we have seen that "grep -i 'american'" yields no match, if we invert the search with -v command
  - it will correspond to all the lines in the file, which is 731 lines.

```
  grep -c "String" file
```
  - This command helps to suppress normal output; instead print a count of matching lines for each input file.
  - 'c' stands for count
  - Here is how it works
  - ![Image](4.11.png)

