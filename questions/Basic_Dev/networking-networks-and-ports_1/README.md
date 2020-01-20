## Jimmy sent a package to Dean and noticed the source port was 51234 and the destination port was 666 on one of the TCP packets.  The difference between these two port types is ___.

KSAs: 216, 217, 1293, 1298

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| port 51234 is assigned by IANA whereas 666 is never assigned. | port 51234 is a registered port whereas 666 is an ephemeral port. | other than the numbers, there is no difference. | ***port 51234 is an ephemeral port whereas 666 is a well-known port.*** |


Feedback:

- IAW RFC 6335, ports 0 - 1023 are considered system, or well-known, ports; 1024 - 49151 are considered user, or registered ports; and 49152 - 65535 are dynamic, private, or ephemeral ports. The dynamic ports are never assigned.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

