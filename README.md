# Linux-Commands
The internsctl command is a custom Linux command designed to retrieve file information, including details like file size, permissions, owner, and last modified date. It provides options to fetch specific details about a given file.
Usage
Getting File Information

To retrieve information about a file, use the following command:

internsctl file getinfo <file-name>
Replace <file-name> with the name of the file you want to retrieve information about. This command will display various details about the specified file, including permissions, size, owner, and last modified date.

Options for Specific Information
The command also provides options to retrieve specific information about the file:

File Size:

bash
Copy code
internsctl file getinfo --size <file-name>
or

bash
Copy code
internsctl file getinfo -s <file-name>
File Permissions:

bash
Copy code
internsctl file getinfo --permissions <file-name>
or

bash
Copy code
internsctl file getinfo -p <file-name>
File Owner:

bash
Copy code
internsctl file getinfo --owner <file-name>
or

bash
Copy code
internsctl file getinfo -o <file-name>
Last Modified Date:

bash
Copy code
internsctl file getinfo --last-modified <file-name>
or

bash
Copy code
internsctl file getinfo -m <file-name>
Replace <file-name> in each command with the actual name of the file.

Example
Getting Information for a File
For example, to get information about a file named hello.txt:

bash
Copy code
internsctl file getinfo hello.txt
This command will display information about the file hello.txt such as permissions, size, owner, and last modified date.

Getting Specific Information
To get only the file size of hello.txt:

bash
Copy code
internsctl file getinfo --size hello.txt
This command will display the size of the file hello.txt.

Note
For running some commands, elevated permissions might be required (e.g., using sudo).

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/26d701cc-0d43-4beb-bff0-29bc41e2162c) 

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/6fd9a14c-077a-446f-8d0f-33d83a6f1030)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/868f0d68-b5a6-48b5-a35f-29a37304fbb6)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/035b32b1-4d47-40c8-b052-7dffccc6df72)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/d8908907-19aa-4c52-9074-59060f816e19)






