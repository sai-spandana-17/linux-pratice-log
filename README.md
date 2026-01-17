
My daily learning notes of linux commands with help of  bandit overthewire.


comands used :

1. ls : to list the file/items present in that directory/folder.
         ex: ls
2.ls -a : shows the hidden files with regular files.
               ex:ls -a 
         
3. cd : to change directory
      ex : cd directoryname
            or
            cd  path/of/directory
            
 4. cat :   to print the text present ti file
            ex:  cat filename
                   cat ./filename
                   cat ./"file name "
 
 5. ssh : to connect teh two systems over networking (working in same network)
             ex ; ssh username@ipaddress
                    ssh username@dns -p portnumber                   
            
 6. find ;  used to find/search files/directories
 
 7. sort : used to sort data in file.
                 ex:  sort filename.txt
 
 8. uniq ; prints the only line which is unique
                  ex: uniq filename.txt
 9. grep : searches the words/lines/charectors present in file
                ex: grep "what you want to search" filename.txt
