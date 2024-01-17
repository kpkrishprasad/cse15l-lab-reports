# cd no input

![Image](cd-no-arg.png)

Working Directory: Home directory (~).  
Explanation: The cd command with no arguments takes you to your home directory. Since you are in the home directory, there is no  change.  
Output: No error since the command executed successfully.  

# ls no input

![Image](ls-no-arg.png)

Working Directory: Home directory (~).  
Explanation: ls with no arguments lists all the items in the current working directory.  
Output: No error as the command listed all of the items in the home directory.  

# cat no input

![Image](cat-no-arg.png)

Working Directory: Home directory (~).  
Explanation: cat without any arguments waits for input from the user in the terminal. The ^C indicates that the user interrupted the command with Ctrl+C.  
Output: No error since the command is waiting for input and can be interrupted by the user.  

# cd directory

![Image](cd-dir-arg.png)

Working Directory: Changed to the lecture1 directory.  
Explanation: The cd command followed by the name of the directory changes the working directory to the specified directory.  
Output: No error since the command executed successfully and changed to lecture1 directory.  

# ls directory

![Image](ls-dir-arg.png)

Working Directory: Home directory (~).  
Explanation: ls followed by a directory name lists all the files and directories within the specified directory.  
Output: No error as the command listed the contents of the lecture1 directory.  

# cat directory

![Image](cat-dir-arg.png)

Working Directory: Home directory (~).  
Explanation: Using cat on a directory causes an error since cat is designed to read and concatenate files, but a directory was given.  
Output: Error because lecture1 is a directory and cannot be read by cat.  

# cd file

![Image](cd-file-arg.png)

Working Directory: the working directory remains the same as the command did not execute successfully (~/lecture1/messages).  
Explanation: Attempting to cd into a file results in an error because cd expects a directory, not a file.  
Output: Error, because en-us.txt is not a directory.  

# ls file

![Image](ls-file-arg.png)

Working Directory: ~/lecture1/messages.  
Explanation: ls followed by a file name will list that file if it exists in the current working directory.  
Output: No error since the command confirmed the existence of the en-us.txt file.  

# cat file

![Image](cat-file-arg.png)

Working Directory: ~/lecture1/messages.  
Explanation: cat followed by a file name displays the content of the file.  
Output: No error as the command displayed the contents of the en-us.txt file.  
