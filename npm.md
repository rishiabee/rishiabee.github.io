# How to set shell for npm run-scripts in windows

Since npm 5.1
: ```npm config set script-shell "C:\\Program Files (x86)\\git\\bin\\bash.exe"  ```
or (64bit installation)
:  ```npm config set script-shell "C:\\Program Files\\git\\bin\\bash.exe"  ```

Revert:
 ```npm config delete script-shell ```
 
  Version | Commande 
 ------------ | -------------
 **x86** | ```npm config set script-shell "C:\\Program Files (x86)\\git\\bin\\bash.exe"``` 
 **64bit** |  ```npm config set script-shell "C:\\Program Files\\git\\bin\\bash.exe"  ``` 
 **Revert** |  ```npm config delete script-shell ``` 
