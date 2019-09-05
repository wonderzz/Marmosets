**Main function**

1、Handling incoming network requests through HTTP and other related protocols.

1.1、 Establish a connection and complete HTTP negotiation (to determine the acceptable processing methods for both parties, including protocol version, encryption, content format, etc.), and further include the determination of user identity dialogue status session.

1.2、Encapsulate the user request content into HTTP packet and send it to the server.

1.3、 Accept the data packets returned by the server and send them back to the client.

  
2、 Store the cached data and return the static resources requested by users directly