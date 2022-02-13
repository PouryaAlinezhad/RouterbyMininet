# RouterbyMininet
impelement a router using miniet
creating attached network using the Mininet Python API, no controller is needed , since
hosts are in different subnets, we need to input a correct flow for the router, which is itself an OVS switch.
The switches are obvious enough, the router however has to read the layer 3 header and decrement
TTL.
