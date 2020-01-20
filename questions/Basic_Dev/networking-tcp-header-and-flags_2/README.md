## In networking, which TCP flag means there is no more data to send?

KSAs: 216, 1298

## Answer
| A | ***B*** | C | D |
| :--- | :--- | :--- | :--- |
| ACK | ***FIN*** | RST | SYN |


Feedback:

- A) Incorrect: The Acknowledgement (ACK) flag confirms the receipt of the prior segment.
- B) Correct: The Fin (FIN) flag signifies a proper termination of the connection, as there is no more data to transmit.
- C) Incorrect: The Reset (RST) flag allows for the spontaneous termination of a connection.
- D) Incorrect: The Synchronize (SYN) flag is the first sent to begin a TCP connection, specifically this flag calls for the hosts to synchronize sequence numbers.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

