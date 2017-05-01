Gscp
===============
2017-05-01


Gui Simple Communication Protocol.



It's a protocol for communication between a gui (graphical user interface) and a server.


How to
============
This is a two step process:

1. The gui can send any data to the server.

2. The server responds with a well formatted json, which is the following array:

- type: string=(error|success), define whether the response is successful or a failure
- data: mixed, accompanying data, interpretation is left to the caller


That's it.
