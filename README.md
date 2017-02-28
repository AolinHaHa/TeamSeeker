# TeamSeeker
Java distributed system
Networking
Identifying Network Interfaces
HostResolve: a host name resolution program
A program that resolves the names of a host to its associated IP address(es).
By default, the program resolves the name of a host provided as a command line argument to a single address.
The program also permit one option, '-a', which directs the program to find all addresses associated with the host name.
Using the InetAddress.getByName() method to find the default address.
Using InetAddress.getAllByName() method to find all addresses for that host name.
Usage:
java HostResolve [-a] [host name]
The program must write the IP address(es) to standard output.
