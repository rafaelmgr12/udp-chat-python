<h1 align="center">UDP Chat Python</h1>
<p align = "center">This is a simple UDP chat application</p>

<p align="center">
  <a href="#-technology">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-run">How to Run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
</p>

## 📖 What is UDP (User Datagram Protocol)?
User Datagram Protocol (UDP) is a lightweight, connectionless communication protocol operating at the transport layer of the Internet Protocol (IP) suite. Unlike TCP, UDP doesn't provide reliability or error correction mechanisms, making it faster and more efficient. UDP is commonly used for real-time applications like streaming, gaming, and VoIP, where speed and low latency are important. It offers flexibility and control over data transmission but sacrifices some reliability guarantees.

## ✨ Technology

The Project was develop as using the following techs:
- Python 3.x
- Socket
- argparse


## 💻 Project

This project is a simplified implementation of a chat application using User Datagram Protocol (UDP). It provides a basic framework for establishing communication between a server and a client using UDP sockets. The server listens for incoming messages on a specified port and sends back a response to the client. The client can input messages and receive replies from the server.

While this project serves as a demonstration of UDP-based communication, it is important to note that it does not include advanced features such as message encryption, authentication, or error handling. It is a starting point for understanding the fundamentals of UDP-based chat applications and can be expanded upon to add additional functionality as needed.


## 🚀 How to Run
To run the this project 

1. Clone the repository:
2. Change to the project directory:
3. Run the server:
```bash
python udp_chat.py server [-p PORT]
```
   * -p PORT: Specify the UDP port number for the server to listen on (default is 3000). The server will start listening for incoming messages on the specified port.
4. Run the client:
```bash
python udp_chat.py client [-p PORT]
```
* -p PORT: Specify the UDP port number to connect to the server (default is 3000).
The client will prompt you to input a message to send to the server. It will then display the server's reply.
5. Start chatting!

You can now exchange messages between the server and the client. Each time the client sends a message, it will wait for the server's reply before sending the next message.

To exit the program, you can simply press Ctrl+C.

## 📄 License
The projects is under the MIT license. See the file [LICENSE](LICENSE) fore more details

---
## Author

Made with ♥ by Rafael 👋🏻


[![Linkedin Badge](https://img.shields.io/badge/-Rafael-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/rafael-mgr/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat-square&link=mailto:nelsonsantosaraujo@hotmail.com)](mailto:ribeirorafaelmatehus@gmail.com)
