# my_sudo 
## Goal of the project  
Recode the sudo command including flags [-sEug]  
## Flags  
All of the flags have a unique usage and can be combined together :  
**`-s`** : launches a shell environment  
**`-E`** : preserve the environment variables  
**`-g`** : execute a command as group  
**`-u`** : execute a command as a user
## Usage
use : **`make run`** to create the **`my_sudo`** exectuable  

./my_sudo <flags> <command> <command_arguments>  
exemples :  
- **`./my_sudo -u leob ls -l`**  
  Will execute ls -l as leob
- **`./my_sudo -u toto -s`**    
  Will launch toto's shell
