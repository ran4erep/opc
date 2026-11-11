# opc
Bash script to easy use Colab CLI + OpenCode

How to use?

Download opc file and just type in your terminal `bash path_to_opc/opc`. You will see installer, it's gonna install dependencies for your machine and also OpenCode and git for Colab's cloud machine. Also it will prompt you to enter your API key for OpenCode and SSH key for git, to connect Github. After installation is finished just type in your terminal `opc` and that's it, you are in Colab CLI cloud machine, OpenCode and git installed, you are already inside of OpenCode, your provider already connected. You are good to go. `ocp` command is global in your system and has a few commands, you can read them by typing `ocp -help`. But here's a list:

```
opc - just connection
opc -help` - list of commands
opc -new` - deletes previous Colab session and creates a new one
opc file.txt` or `opc file.txt file2.txt` - connects and uploads selected files
opc -all` connect and uploads all files from current directory
opc -api` - change saved provider and API key
opc -sshkey` - change saved SSH key for Github connection
opc -collect` - downloads all files from the current Colab session as .zip archive
```
