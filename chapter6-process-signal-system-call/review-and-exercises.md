## True or False
1. If a process tries to read from an open pipe before there is any data in the Pipe, it could get an error. (2017 APRIL)

***ANSWER***: read will be blocked until at least one byte has been written to the pipe. 