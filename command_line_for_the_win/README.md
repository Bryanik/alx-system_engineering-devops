# Command line for the win
## How to use SFTP command-line tool to move your local screenshots to the sandbox environment
1. Open `Command Prompt` app on windows system.
2. Connect to sandbox using the command `sftp Username@Host`. Both Username and Host can be found on the intranet.
3. Enter Sandbox password to connect. Password can be found on the intranet.
4. After successful connection, navigate to the directory in the sandbox where you want to store the uploaded files, using `cd` command.
5. Navigate to the folder in local system containing the files you intend to upload using `lcd ` command.
6. Upload each files from local system to sandbox using the command `put file_name`
7. Confirm the files have been uploaded to the sandbox  using `ls` command.
8. Exit SFTP connection using `bye` command.
