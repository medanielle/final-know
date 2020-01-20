## In networking, which Python function converts 16-bit positive integers from network to host byte order?

KSAs: 240

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| socket.ntohl(x) | ***socket.ntohs(x)*** | socket.htonl(x) | socket.htons(x) |


Feedback:

- A) Incorrect: ntohl() function converts a 32 bit integer from network order to host order.
- B) Correct: ntohs() function converts a 16 bit integer from network format to host format.
- C) Incorrect: htonl() function converts a 32 bit positive integer from host byte order to network byte order.
- D) Incorrect: htons() function converts a 16 bit positive integer from host byte order to network byte order.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

