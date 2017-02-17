# Performance

This is the load test of Bitsocket running on low cost (1$ per month) virtual server with following configuration:

- VMware hypervisor
- CPU 1vCore
- RAM 1GB

## Results

### Latency per clients
First test distributed 1 message per second. Every two minutes 100 clients has been connected. Following graph shows latency in various percentiles for amount of connected clients. 

![performance results](assets/images/perf1.png "Performance results 1")

If we send 2 messages per second, distribution is working nearly same until 3000 clients. This is the cap for given server configuration.

![performance results](assets/images/perf2.png "Performance results 2")

Network latencies are not included.

### Latency per messages

TODO