# Unix commands
A collection of useful Unix commands for various tasks.

## zip/tar
1) unzip files from zip to another folder - extract in folder (assumes location exists)
```shell
unzip /path/to/file.zip -d /path/to/extraction/directory
```
## SoX - sound exchange
1) convert gsm files to .wav
```shell
sox -S 8000 <input.gsm> <output.wav>
```

## Screen
1) list screens
```shell
screen -ls
```
2) resume screen
```shell
screen -r <pid of screen you wish to resume>
``` 
3) kill screen
```shell
screen -X -S <pid of screen you wish to kill> quit
``` 