Create your own system call in C, called sh task info(), which takes argument as PID. It would need to search out the task struct() corresponding to the PID and print out all the fields corresponding to it and also save it in a file. The file name also needs to be supplied as an argument to the
system call.
You also would require to handle errors in user inputs, such as incorrect arguments, through appropriate errno and function return values (e.g. 0 signaling correct input, while 1 signaling incorrect input).
Using Linux/kernel v5.9 distribution ,i.e. the system call is written for the said version. 
