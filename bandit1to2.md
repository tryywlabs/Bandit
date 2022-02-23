Key Commands:
- ls: lists files in the current directory.
- ls -l: lists files in the current directory in separate lines.
- ls -al: includes hidden files (files starting with '.').
- cat: concatenates chosen file by standard output.
- file: outputs file type.
- find: searches for files in directory.

Steps:
1. Login to bandit1 using ssh connection.
2. Logging in will place you in the home directory. Run 'ls' to list the files in the directory.
3. There will be a file by the name -. Concatenate the file by running "cat '-'". This will output the flag.
4. Obtain the flag and end the ssh connection to bandit1 by running 'exit'.

Key Terms:
- SSH: Secure Shell Protocol. Cryptographic network protocol for operating network connections securely over an unsecure network. Used for remote logins and commandline execution. SSH encrypts all network calls from and to the server and client.
