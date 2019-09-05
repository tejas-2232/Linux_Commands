# Linux_Commands
## we will see essential linux commands and cool tricks here. 
#### If you are new to linux and you got stuck somewhere in between this is right repo for you
##### 1. To unlock a file or folder(which shows lock icon): If you see the lock icon on file/folder it means you cant delete it. To do the job one has to give read, write and execute permission through commands. we will see them one by one.

##### Giving all permission(read,write,execute): -> sudo chmod 777 -R /path_to_folder

   The permissions (Here 777) are as follow:
      7 - Full (Read, Write & Execute)
      6 - read and write
      5 - read and execute
      4 - read only
      3 - write and execute
      2 - write only
      1 - execute only
      0 - none
      
     
     
###### First number change Ownership of file, second affect Group of users can access, and third refers to Others user.
       7-OWNER      
       7-GROUP
       7-OTHER
       
###### After changing the permission,delete the folder
