# Char-Driver-new_features
It is a char-driver which can do both read and write operations.
Using the echo command u could write into a device buffer which is located in the kernel space..This is handled by the write function created by me.
Now in order to read the data from the kernel space,u can use the cat command and this function is handled by the read function..

This driver will make u communicate from the user space to kernel space and vice versa. 

