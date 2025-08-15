# Multi-Threaded Pub/Sub Broker with Topic-Based Load Distribution | Course Project (CS744)

* Developed a multi-threaded TCP publish–subscribe broker in C using pthreads and mutex-protected data structures to deliver real-time messages to thousands of subscribers.
* Engineered publisher and subscriber clients with a Bash-based load generator, leveraging cached broker connections to benchmark throughput under high concurrency.
* Designed a modular-hash load-balancing scheme to evenly distribute topics across brokers, enabling scalable multi-broker deployments.
