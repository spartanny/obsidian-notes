
https://highscalability.com/gossip-protocol-explained/

what's the issue (particularly for distributed systems)
- Maintain the system state (liveliness of nodes)
- communication between nodes 

possible solution and drawbacks
- Centralised state management : eg Apache zookeeper. but this can only hold for soo long when you'll start encountering scalability issues and ultimately this will be the SPOF
- P2P communication
	- **Point-to-point broadcast** 
		![[Pasted image 20240910102758.png]]
	
	- **Eager reliable broadcast**
		Every node rebroadcasts message to other possible nodes . 
		Significant network bandwidth usage due to O(n²) messages being broadcast for _n_ number of nodes
		Every node stores the list of all the nodes in the system causing increased storage costs
	
	- **Gossip protocol**





TODO :  ### Gossip Protocol Implementation
