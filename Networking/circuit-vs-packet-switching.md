# Circuit switching vs Package switching

## Circuit Switching

- Circuit Switching is a connection-oriented service. It provides a dedicated path from the sender to the receiver.

### Advantages of Circuit Switching

- Fixed bandwidth.
- A dedicated communication channel increases the quality of communication.
- Data is transmitted with a fixed data rate.
- No waiting time at switches.
- Suitable for long continuous communication.

### Disadvantages of Circuit Switching

- A dedicated connection makes it impossible to transmit other data even if the channel is free.
- Resources are not utilized fully.
- The time required to establish the physical link between the two stations is too long.
- A dedicated path has to be established for each connection.
- Circuit switching is more expensive.
- Even if there is no transfer of data, the link is still maintained until it is terminated by users.

## Packet Switching

- Packet switching is a connection-less service. It does not require any dedicated path between the sender and receiver.

### Advantages of Packet Switching

- It reduces access delay.
- Costs are minimized to great extent.
- Packets are rerouted in case of any problems. This ensures reliable communication.
- It is more efficient for data transmission because no need to establish the path.
- Several users can share the same channel simultaneously. Therefore packet switching makes use of available bandwidth efficiently.

### Disadvantages of Packet Switching

- In packet switching, the network can not be used in applications requiring very little delay and higher quality of service.
- Protocols used in the packet switching are complex.
- If the network becomes overloaded, packets are delayed or discarded, or dropped. This leads to the retransmission of lost packets by the sender.
- It is not secured if security protocols are not used during packet transmission.

|                                      Circuit Switching                                      |                                        Packet Switching                                       |   |   |   |
|:-------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|---|---|---|
| Circuit switching requires a dedicated path before sending data from source to destination. | Packet switching does not require any dedicated path to send data from source to destination. |   |   |   |
| It reserves the entire bandwidth in advance.                                                | It does not reserve bandwidth in advance                                                      |   |   |   |
| No store and forward transmission                                                           | It supports store and forward transmission                                                    |   |   |   |
| Each packet follows the same route                                                          | A packet can follow any route                                                                 |   |   |   |
| Call setup is required                                                                      | No call setup is required                                                                     |   |   |   |
| Bandwidth wastage                                                                           | No bandwidth wastage                                                                          |   |   |   |