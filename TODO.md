- [ ]  Mark suitable pointers with the `restrict` keyword
- [ ]  Extract the client disconnect logic into a separate function
- [ ]  Implement a proper memory strategy that doesn't impose a limit on the number of connected users and, if possible, doesn't require that much mutually-exclusive access from different threads (i.e. one that's more multithread-friendly)
- [ ]  Use a memory pool for the message buffers
- [ ]  Implement another strategy using AcceptEx instead of accept
- [ ]  Send messages asynchronously (i.e. use WSASend instead of send)
