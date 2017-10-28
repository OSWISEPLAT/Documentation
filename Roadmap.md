WISEPLAT Software Roadmap
-----------------------

This document outlines the high level of development plan and will be updated. 
It should be noted that this roadmap applies only to the blockchain software.
Other tools and utilities such as wallets and block explorers will have their own
teams and roadmaps.

***Everything contained in this document is in draft form and subject to change at any time and provided for information purposes only. WISEPLAT does not guarantee the accuracy of the information and conclusions contained in this roadmap and the information is provided “as is” with no representations or warranties, express or implied.***

# Step 1 - Minimal Test Environment - January-February 2018

### Standalone Node 
A full node which one can fully operate on a test blockchain and produces blocks. 

### Core Contracts 
Contracts are implemented at core level. These are contracts that manage the core operations of the blockchain like token transfers, voting, settings permissions, messages, and contact code updates.

### Virtual Machine API
Contracts are compiled to WebAssembly (WASM) and WASM must interface with the blockchain via a defined
API.

### RPC Interface
A simple JSON RPC over HTTP interface will be provided.

### Command line Tools
They will facilitate integrating the RPC interface with developer build environments. 

### Basic Developer Documentation
Tutorials and Guides for WISEPLAT blockchain and documentations for the WASM API, RPC Interface, and Command Line Tools.


# Step 2 - Full Test Environment - March-April 2018

### Several Nodes
The full nodes are geographically distributed.

### P2P Network Code
Nodes are synchronizing the blockchain state between them.  

### WASM Sanitation & Sandboxing
Code will be sanitized to check for non-deterministic behavior such as floating point operations and infinite loops.  

### Resource Usage Tracking & Rate Limiting
Resource monitoring and usage tracking.

### Interblockchain Communication
Verifying the Merkle hashing of transactions is proper.

### Genesis generation


# Step 3 - Testing & Security Audits - May-June 2018

### Massive testing
Testing under heavy loads.

### Search for non-deterministic behavior
Search nondeterministic behavior.

### Search for vulnerabilities
Attacking the network with spam, exploits, and bug crashes.

### Payment of awards for finded bugs
Bounties for Succesfully Attacking.

# Step 4 - Systems optimizations - July-August 2018

### Increase the capacity of the nodes
Adding nodes to improve scalability.

### Geographically area nodes
Geographically distributed nodes for fault tolerance.

### Monitoring of loads
Monitoring the load and looking for bottlenecks.

# Step 5 - Starting Production Clusters - September-October 2018

### Start nodes in production environment (version 1.0)
Expand productive environment for WISEPLAT.

### Start application development
Starting to build applications for WISEPLAT.



