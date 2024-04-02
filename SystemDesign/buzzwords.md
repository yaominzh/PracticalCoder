# table


number | word | meaning | example
--- | --- | --- | ---
00 | Scalability| By adding servers, the capacity of the application/service can be increased seamlessly| Load balancers make such upscaling or downscaling transparent to the end users.
01 | Availability| Even if some servers go down or suffer a fault, the system still remains available | One of the jobs of the load balancers is to hide faults and failures of servers.
02 | Performance| Load balancers can forward requests to servers with a lesser load so the user can get a quicker response time. This not only improves performance but also improves resource utilization.
03 | DNS as a LB | DNS can be considered a global server load balancer (GSLB).
04 | lb algorithms | RR, weight-RR, least connections, least response time, least bandwidth, least packets, source IP hash, URL hash, custom hash, and random.
10 | Atomicity | It’s either all or nothing |
11 | Consistency | This concerns the correctness of the data. |
12 | Isolation | The database should be able to process concurrent transactions without leading to inconsistency. |
13 | Durability | Once a transaction has been completed the changes are permanently written to disk and won’t be lost in case of a system failure. |

