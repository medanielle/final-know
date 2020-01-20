## Which of the following are valid IPV6 addresses?

KSAs: 230, 233

## Answer
| A | B | C | ***D*** |
| :--- | :--- | :--- | :--- |
| 2001:0db8:0000:0000:0000:ff00:0042:8329 | 2001:db8:0:0:0:ff00:42:8329 | 2001:db8::ff00:42:8329 | ***All of the above*** |


Feedback:

- A) IPv6 addresses are 128 bits long and represented by groups of 1-4 hex characters separated by a :
- B) Using the recommendations in RFC5952 section 4.2 we can shorten that IPv6 address. Leading 0's in a grouping may be omitted.
- C) It may contain at MOST a single :: which represents the largest contiguous block (longer than 16 bits) of 0's in the address
- D) all are correct

[**<- Back To Basic Dev**](../../../Basic_Dev.md)

