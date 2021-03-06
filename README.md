# CPSC351-Project-3-Bankers-Algorithm

The simulation should contain the essentials of the Banker's Algorithm, customers(threads) should make requests of the banker for a limited set of resources. The banker should check whether the customer is exceeding the maximum number of resources he/she said it would ever request, and if there are sufficient system resources, and if the request would put the system in an unsafe state. To determine if the system would be in an unsafe state, the algorithm should attempt to grant the request, by increasing the resources allocated to the given process, and by reducing the total resources still needed by it to satisfy the maximum resources it needs. If there is a still a path of allocating resources and having them released that will satisfy all of the processes that are running, then the system is in a safe state, and the request should be approved.

Only safe requests should be approved.
