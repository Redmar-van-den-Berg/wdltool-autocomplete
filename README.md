# wdltool-autocomplete
Full bash autocompletion for wdltool

Simply source this file from bash to get autocompletion for wdltool, for example from your Downloads folder. 
```
source ~/Downloads/wdltool
```

If your wdltool executable is called something else, you'll have to modify the last line. 
For example, if you just downloaded the jar file and put it in your PATH, change the last line to:
```
complete -F _wdl wdltool-0.8.jar
```
