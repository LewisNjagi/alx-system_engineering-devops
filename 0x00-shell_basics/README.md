pwd = This script prints the absolute path name of the current working directory.                                                                      
ls = Display the contents list of your current directory.                                                                                              
cd = Changes the working directory to the user’s home directory.                                                                                       
ls -l = Display current directory contents in a long format.                                                                                           
ls -al = Display current directory contents, including hidden files with long format.                                                                  
ls -n -a = Display current directory contents with long format,with user and group IDs displayed numerically and hidden files.                         
/tmp/my_first_directory = Creates a directory named my_first_directory in the /tmp/ directory.                                                         
mv /tmp/betty /tmp/my_first_directory = Moves the file betty from /tmp/ to /tmp/my_first_directory.                                                    
rm /tmp/my_first_directory/betty = Deletes the file betty.                                                                                             
rm -r /tmp/my_first_directory = Deletes the directory my_first_directory that is in the /tmp directory.                                                
cd - = Changes the working directory to the previous one.                                                                                              
ls -l -a . .. /boot = Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and 
the parent of the working directory and the /boot directory (in this order), in long format.                                                           
file /tmp/iamafile = Prints the type of the file named iamafile. The file iamafile will be in the /tmp directory.                                      
ln -s /bin/ls ./__ls__ = Creates a symbolic link to /bin/ls, named __ls__.                                                                             
cp -u ./*.html ../ = Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did 
not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.