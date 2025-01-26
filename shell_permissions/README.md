0. My name is Betty
File: 0-iam_betty
Description: Switches the current user to the user betty.
Command: The script uses exactly 8 characters for the command and assumes that the user betty exists on the system.

1. Who am I
File: 1-who_am_i
Description: Prints the effective username of the current user.

2. Empty!
File: 4-empty
Description: Creates an empty file named hello in the current working directory.

3. Execute
File: 5-execute
Description: Adds execute permission to the owner of the file hello.
Note: The file hello must be in the working directory.

4. Multiple permissions
File: 6-multiple_permissions
Description: Adds:

Execute permission to the owner and group owner.
Read permission to others for the file hello.
Note: The file hello must be in the working directory.
5. John Doe
File: 9-John_Doe
Description: Sets the mode of the file hello to -rwxr-x-wx.
Mode Explanation:

Owner: Read, write, and execute (rwx).
Group: Read and execute (r-x).
Others: Write and execute (-wx).
