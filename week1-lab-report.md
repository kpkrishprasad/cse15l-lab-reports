# cd no input

![Image](cd-no-arg.png)

Working Directory: Home directory (~).  
Explanation: The cd command without any arguments takes the user back to their home directory. Since the user is already in the home directory, there is no visible change.  
Output: No error, the command executed successfully.  

# ls no input

![Image](ls-no-arg.png)

Working Directory: Home directory (~).  
Explanation: ls without any arguments lists all the files and directories in the current working directory.  
Output: No error, the command listed the contents of the home directory.  
# cat no input

![Image](cat-no-arg.png)

Working Directory: Home directory (~).  
Explanation: cat without any arguments waits for input from the user in the terminal. The ^C indicates that the user interrupted the command with Ctrl+C.  
Output: No error, the command is waiting for input and can be interrupted by the user.  

# cd directory

![Image](cd-dir-arg.png)

Working Directory: Changed to the lecture1 directory.  
Explanation: The cd command followed by a directory name changes the current working directory to the specified directory.  
Output: No error, the command executed successfully and changed the directory to lecture1.  

# ls directory

![Image](ls-dir-arg.png)

Working Directory: Home directory (~).  
Explanation: ls followed by a directory name lists all the files and directories within the specified directory.  
Output: No error, the command listed the contents of the lecture1 directory.  

# cat directory

![Image](cat-dir-arg.png)

Working Directory: Home directory (~).  
Explanation: Using cat on a directory results in an error because cat is designed to read and concatenate files, not directories.  
Output: Error, because lecture1 is a directory and cannot be read by cat.  

# cd file

![Image](cd-file-arg.png)

Working Directory: Remains the same as the command did not execute successfully (~/lecture1/messages).  
Explanation: Attempting to cd into a file results in an error because cd expects a directory, not a file.  
Output: Error, because en-us.txt is not a directory.  

# ls file

![Image](ls-file-arg.png)

Working Directory: ~/lecture1/messages.  
Explanation: ls followed by a file name will list that file if it exists in the current working directory.  
Output: No error, the command confirmed the existence of the en-us.txt file.  

# cat file

![Image](cat-file-arg.png)

Working Directory: ~/lecture1/messages.  
Explanation: cat followed by a file name displays the content of the file.  
Output: No error, the command displayed the contents of the en-us.txt file.  
