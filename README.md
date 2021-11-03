# p2p-IPv4-offset
Algorithm for an IP sender and an IP receiver to agree on an ESCAPE packet's TCP Checksum hex value and to establish an OFFSET hex value for receiver to translate subsequent TCP Checksums received back to the sender's original intended two bytes per TCP Checksum, regardless of port forwarding via NATs, if any.
