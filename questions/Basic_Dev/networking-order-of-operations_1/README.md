## Which Python function waits for a client to connect on the port?

KSAs: 219, 220, 1305

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| close() | ***listen()*** | accept() | recv() |


Feedback:

- A) Incorrect: close() closes the socket.
- B) Correct: listen() listens for connections made to the socket.
- C) Incorrect: accept() accepts a connection but does not start listening for data.
- D) Incorrect: recv() receives data from the socket.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

