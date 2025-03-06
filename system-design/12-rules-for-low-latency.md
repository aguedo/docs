# Rules for Low Latency

1. Use database index to reduce access time
2. Compress payload to reduce data transfer time
3. Group requests to reduce network overhead and round trips
4. Use HTTP 2 to send requests in parallel through multiplexing
5. Use CDN to keep data closer to the users and reduce round-trip time
6. Reduce external dependencies to minimize unnecessary network calls
7. Add a load balancer to distribute traffic uniformly and reduce server load
8. Scale vertically with better memory and storage for faster processing time
9. Use a message queue to handle compute-intensive tasks in the background
10. Use cache to serve popular data from memory instead of querying the database
11. Use connection pooling for databases and networks to avoid connection overhead
12. Use efficient data serialization format, such as protobuf, to reduce processing time
