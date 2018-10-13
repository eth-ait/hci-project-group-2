# High-level properties of the network
Those are the properties/requirements we need to visualize to the user on the network. E.g. in NetComplete the user provides such requirements together with a configuration sketch. NetComplete then generates a network configuration which fulfills the requirements. The user should be able to inspect the requirements in the resulting network graph.

By looking at the resources listed below we identified the following requirements:
- Failure resistency / N-connectivity
  - Example input: The network should tolerate X node failures (or Y link failures)
- Option to allow clients to announce only their IP range and to receive only their traffic
  - Example input: A list of which clients own which address spaces
- Reachability
- Security: 
  - Path from A to B should not cross (or alternative should always go) through C
  - Access control
   - Example input: A should only be reachable from B, not from other nodes
- Load balancing
  - Example input: Use X paths from A to B with equivalent load
- Resource management
  - Example input: Use server X as few as possible (e.g. because it is old and slow)
- Preferential routing
  - Example input: For connection A to B, use with priority 1 path X, with priority 2 path Y, ...

## Resources
Papers:
- https://www.usenix.org/system/files/conference/nsdi15/nsdi15-paper-fogel.pdf
- https://netcomplete.ethz.ch/files/netcomplete-nsdi2018.pdf
- http://www.konne.me/assets/bagpipe.pdf
- https://ratul.org/papers/sigcomm2016-propane.pdf

Projects:
- https://propane-lang.org/
- https://www.batfish.org
- https://netcomplete.ethz.ch/
- http://www.konne.me/bagpipe/

Startups:
- https://www.forwardnetworks.com
- https://www.intentionet.com
- https://www.veriflow.net

