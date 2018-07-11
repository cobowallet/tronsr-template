## Tron Super Representatives Nodes

Cobo is contributing three Super Representatives
### Node 1.
Name: http://cobo.com
Address: TGnTYAB6XjLWoAGYXmDoLeLeX9X59JFBVK
Reward policy: If the node is elected to be a block producer, Cobo will return all the block producer incentives to the voters.

### Node 2.
Name: http://cobo.com
Address: TMNUDeyr6ZEW8vHAUnaKi2Bbgi14TPq63q
Reward policy: If the node is elected to be a block producer, Cobo will return all the block producer incentives to the voters.

### Node 3.
Name: http://cobo.com
Address: TL8rrg2ZNPHtpPFp3j2nwH9BLhN7qg32dh
Reward policy: If the node is elected to be a block producer, Cobo will return all the block producer incentives to the voters.

### Plan for hardware expansion
Initially, each Super Representative consists of 3 main nodes and 1 backup node. Every server node will be automatically monitored 24/7 with real time operation alerts. We will make sure every server nodes are healthy, which means average CPU utilization rate is below 45%, and peaks below 75%, memory and bandwidth utilization are to be kept below 40% for each server. If the threshold is exceeded, we will upgrade the server hardware, or add more server nodes with proper load balancing.

Cobo has designated two front-end engineers, two backend engineers and one senior site reliability engineer to support the Tron Super Representatives, contribute to the Tron community, and actively develop TRX related tool chains, e,g, wallet, voting, etc.

## Server Location
Every Tron Super representative node is running in a secure cloud center, across the world ( Japan, North America, China, and Europe). Initially, each Super Representative consistent with 3 main nodes and 1 backup node.

## Server Configuration
### Main node plan
* Instance: ECS.CE4.xlarge
* Type: High Frequency / High MEM, Optimized I/O
* vCPU: 64
* Memory: 128 GB
* SSD: 20T
* Process: 64vCPU
* Network: Virtual Private
* Bandwidth: 25G

### Slave (backup) node plan
* Instance: ECS.CE4.xlarge
* Type: High Frequency / High MEM, Optimized I/O
* vCPU: 32
* Memory: 64 GB
* SSD: 20T
* Process: 32vCPU
* Network: Virtual Private
* Bandwidth: 25G
