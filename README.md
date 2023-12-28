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

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/a618e76c-46ff-45d9-b340-799cf5f4ff9a)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/b9faceb4-2c6f-4894-a8fb-e3f9337d1e8f)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/e3187621-b393-482e-b95e-fe204574f8d2)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/0a3be196-2962-41a1-8c24-8bba6b69be85)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/1819b73e-6ca6-4130-9ea0-82cb5ade00bf)

![image](https://github.com/Ishikamishra/Linux-Commands/assets/81811063/109b462d-8cde-4952-a11f-1ad5aca29612)



