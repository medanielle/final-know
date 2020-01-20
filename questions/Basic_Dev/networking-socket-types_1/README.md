## A TCP socket is different from a UDP socket because ___.

KSAs: 216, 217, 219, 220, 1298, 1305

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| you have to specify both the IP address and the port, compared to UDP only requiring the IP address | the TCP socket works in a send and forget model | ***you have to connect to a remote node prior to sending a message*** | the socket doesn't have to be closed when communication is finished like you would do with a UDP socket |


Feedback:

- Both TCP and UDP sockets require the IP address and port number of the destination node for proper communication and both should always be closed when finished. Since TCP is connection oriented, a connection must first be established before sending messages through a socket; UDP doesn't require a connection because it's connection-less.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

