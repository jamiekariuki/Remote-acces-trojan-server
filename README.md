# Malware Server

The Malware Server is a component  focused on cybersecurity and malware development. It acts as the command and control server for a malware application. Please note that this project is strictly for educational purposes only. It is essential to adhere to ethical guidelines and refrain from using this code for any malicious activities.

## Features

### Remote Command Execution
The Malware Server allows remote control of compromised machines. It listens for connections from infected systems and executes commands sent by the malware. This feature enables various actions on the compromised machines, including executing shell commands, changing directories, enabling persistence, and more.

### Persistence
The server supports the persistence feature, enabling the malware to achieve persistence on infected systems. By enabling persistence, the malware ensures that it runs automatically every time the user logs on to the compromised machine.

### Keylogger Monitoring
The server includes keylogger monitoring capabilities. It captures and receives keyboard inputs from infected machines, allowing for monitoring of keystrokes. This feature provides valuable insights into potential security vulnerabilities and demonstrates the risks associated with keyloggers.

## Prerequisites
To set up and run the Malware Server, ensure you have the following prerequisites:
- Kali linux


## Usage
To utilize the Malware Server and communicate with infected machines, perform the following steps:
1. Set up a remote server environment to host the Malware Server.
2. Compile and run the server code on your server machine.
3. Modify the server code to set the appropriate IP address and port for your remote server configuration.
4. Start the server, which will listen for incoming connections from infected machines.
5. Once a connection is established, the server will prompt you to enter commands.
6. Enter commands to control the infected machines. Supported commands include:
   - `q`: Close the connection and exit the server.
   - `cd <directory>`: Change the current working directory on the infected system.
   - `persist`: Enable persistence by adding a registry key for the malware to run on system startup.
   - `keylog_start`: Start the keylogger functionality on the infected machine.
   - [Add any other supported commands and their descriptions]
7. The server will send the commands to the infected machines and display the responses received from them.

**Warning: Please exercise extreme caution when using or running this code. It is essential to use this code responsibly and solely for educational purposes. Unauthorized access or unauthorized use of computer systems is illegal and unethical. The project authors and contributors do not endorse or support any malicious activities.**

## Contribution
Contributions to this project are not accepted, it is intended for personal learning and educational purposes only. However, you are welcome to fork the repository and use the code as a reference for your own educational endeavors.


