# test
#### Try compiling & running respective C files each in root and root/folder1 directory

- multiple jobs run parallely - if order is important, use ```need: <job>```
- multiple bash commands can be executed with 
``` 
run : |
  pwd
  ls
  cd folder1
```
- ```uses: actions/checkout@v2``` is **necessary** in order to access repo files through bash command
- ```cd``` in previous run is not reflected in later runs
