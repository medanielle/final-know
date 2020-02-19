## What is one difference between the Open Systems Interconnection (OSI) Network and Transport Layers?

KSAs: 218

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| The Network layer is divided into two sublayers: Logical Link Control (LLC) and Media Access control (MAC); whereas the Transport layer performs segmentation and flow control. | The Network layer takes information it receives from the session layer and passes it to the Transport layer; the transport layer then passes this information to the data link layer. | ***The Network layer is responsible for routing and addressing whereas the Transport layer handles end-to-end delivery of a message.*** | The Network layer provides connection oriented and connection-less services whereas the Transport layer is responsible for establishing, using, and terminating a connection. |


Feedback:

- A) Incorrect: The Data Link layer is divided into LLC and MAC layers, not the Network layer.
- B) Incorrect: The Network layer takes information it receives from the Transport layer and passes it to the Data Link layer; the reverse is also true. The Transport layer passes information between the Network and Session layers.
- C) Correct: The network layer handles routing and addressing and the transport layer takes care of end-to-end message delivery.
- D) Incorrect: The transport layer is responsible for connection oriented and connection-less services, not the Network layer, and the Session layer handles establishing, using, and terminating connections, not the Transport layer.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

