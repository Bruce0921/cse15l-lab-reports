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
  grep . -type f
```
  - This command helps to find type f of files in the provided directory
  - It works like this
  - ![Image](4.8.png)
