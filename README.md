# MULTITHREADED-CHAT-APPLICATION
Company:CODTECH IT SOLUTION

Name:Ashwin Pradeep Pai

Intern Id:CT04DG64

Domain:Java Programming

Duration:4 Week

Mentor:NEELA SANTOSH

Output:


![Image](https://github.com/user-attachments/assets/f9aa09fb-37f0-4a20-8c9a-7f10b634d95d)



![Image](https://github.com/user-attachments/assets/d2d284fb-ec5a-448f-a78d-0f8b5630e381)




![Image](https://github.com/user-attachments/assets/a567413e-94f5-40dd-aa6a-c100b0012fc9)


Description:A client-server chat application using Java sockets and multithreading is a network-based program that facilitates real-time communication between multiple users by establishing a connection between clients and a central server. The server is responsible for accepting incoming client connections via a ServerSocket, and each client connects to the server using a Socket. Once a client is connected, a separate thread is spawned to handle communication with that specific client using the ClientHandler class, which implements Runnable. This design ensures that the server can handle multiple clients simultaneously without blocking, enabling concurrent message exchange. Each client sends a username upon joining, and any messages typed by that client are broadcasted to all other connected users through shared resources managed by the server. This is achieved using buffered input and output streams (BufferedReader and BufferedWriter) to read from and write to the sockets efficiently. The server maintains a static list of all active client handlers, and every incoming message is propagated to every client except the sender, promoting a group chat-like environment. Clients also run a background thread to constantly listen for incoming messages from the server, ensuring a seamless chat experience. This architecture makes use of core Java networking libraries and demonstrates how socket programming, combined with multithreading, can be utilized to build scalable, interactive, and real-time communication applications. By managing socket connections and handling input/output streams effectively, this chat system showcases how Java enables asynchronous operations and concurrent processing. The approach adheres to the client-server model, where the server remains central and clients act as endpoints. Furthermore, the modular structure, split across three classes (Server, ClientHandler, and Client), promotes code clarity, maintainability, and extensibility. This makes it a suitable foundational project for understanding multithreading, socket communication, and network-based application development. The system can easily be extended to include features like private messaging, file sharing, or graphical user interfaces (GUIs) using Java Swing or JavaFX. Overall, this Java-based multithreaded chat application serves as a practical implementation of network programming concepts and fulfills the criteria of handling multiple clients concurrently through efficient socket and thread management.
