# Bandit-0-5
Bandit 0-5
This script completes the first five levels of the Over The Wire's Bandit game which is located on a remote server accessible via a ssh connection.
The script then goes through each level, executing commands to locate a file with the next password which is then supplied to another function reach the next round.
The script contains eight fucntions in total, six for each of the levels and two establishing and closing the ssh connections.
The script uses two external modules: paramiko and ConfigParser. Paramiko is used for logging in and communicating with the remote server, and ConfigParser is extracting the login details such as address and usernames from cfg files.
There are six cfig files, each with specific login information for each level. These files do not contain any passwords with the exception for level zero.
The script generates a txt file called "passwords" where all the passwords, that is six in total, are stored and prove that the program run succesfully.
