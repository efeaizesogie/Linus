# A folder called ‘projects’ exists in the home directory or the user ‘alfred’. The folder has the user group ‘admin’.
List out the commands to move the folder ‘projects’ to the user ‘alfred’ document folder
List out the commands to change the user group of the ‘projects’ folder to ‘public’
List out the commands to change the owner of the ‘projects’ folder to ‘root’


## Move the folder 'projects' to the user 'alfred' document folder:
    mv /home/alfred/projects /home/alfred/Documents
## Change the user group of the 'projects' folder to 'public':
    chgrp public /home/alfred/Documents/projects
## Change the owner of the 'projects' folder to 'root':
    chown /home/alfred/Documents/projects
