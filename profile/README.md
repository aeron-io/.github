# Aeron -- the global technology standard for high-throughput, low-latency, fault-tolerant trading systems.

## Aeron Transport
Aeron is the world’s leading low-latency message transport system, designed for performance, reliability, and observability. It provides secure streams for unicast and multicast communication, both on-prem and in the cloud, as well as IPC message transport for messaging on a single host. Aeron supports Java, C/C++, and .NET, ensuring broad compatibility. It delivers predictable latency in single-digit microseconds and achieves throughput of over 20 million messages per second, making it ideal for real-time applications.

## Aeron Archive
Aeron Archive extends Aeron Transport by providing a robust solution for message archiving and replay. It allows message streams to be persisted to disk at full message rate, enabling replay in real-time or at a later date. This ensures that any service that becomes disconnected can reconnect and reliably recover without message loss. Aeron Archive supports efficient recording of streams to disk, with or without active subscriptions, and can spy on active publications. It allows replay from specific positions in a recording, either directly from an archive or merged with a real-time stream. Additionally, it supports replication of recordings from a source process to a destination process, useful for near real-time backup of data. The archive can be managed flexibly, allowing for purging, truncating, or applying CRC checks to archived data.

## Aeron Cluster
Aeron Cluster is the world’s leading framework for high-performance, in-memory, fault-tolerant transactional services. It enables resilient 24/7 workloads in the cloud, on-prem, or in a hybrid environment. With automatic failover and data loss SLAs into the 99.999th percentile, failover takes less than a second, minimizing business impact and ensuring critical data retention. Aeron Cluster is fault-tolerant, strongly consistent, and supports zero downtime upgrades. It achieves throughput of many millions of messages per second with predictable latency as low as 18 microseconds on-prem and sub-50 microseconds in the cloud. It sequences and reliably replicates transactional messages at massive scale, making it ideal for capital markets systems that demand 24/7 uptime and stateful recovery with no data loss. Aeron Cluster is suitable for running exchanges, RFQ, IOI, or similar workflows.

## Agrona
Agrona is a library of high-performance data structures and utility methods for Java. It is designed to be used in low-latency, high-throughput applications, providing efficient and reliable data handling. Agrona includes various data structures such as ring buffers, queues, and maps, optimized for performance and minimal garbage collection.

## Simple Binary Encoding (SBE)
SBE is a high-performance message codec designed for low-latency applications. It provides a compact binary encoding format that minimizes message size and maximizes encoding/decoding speed. SBE is ideal for financial applications, where performance and efficiency are critical. It supports schema evolution, allowing for backward and forward compatibility of messages.

## Why Aeron?
Aeron offers unparalleled performance and reliability for messaging and data solutions. By leveraging Aeron Transport, Archive, Cluster, Agrona, and SBE, applications can achieve:
- **Low Latency**: Consistent low-latency communication for real-time applications.
- **High Throughput**: Efficient message transport capable of handling high volumes of data.
- **Fault Tolerance**: High-availability and fault-tolerant architecture for mission-critical applications.
- **Scalability**: Seamless scalability to meet the growing demands of modern distributed systems, including suitability for cloud environments.

Aeron also offer a range of premium components and support, find out more on our [website](https://aeron.io).

Find the full documentation and explore more [here](https://aeron.io/docs).

Aeron is sponsored by [Adaptive](https://weareadaptive.com)

[Aeron Trademark Policy](https://aeron.io/aeron-open-source-trade-mark-policy/)
