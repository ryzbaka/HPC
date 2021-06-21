# Metrics and Evaluation

In order to design better computer architecture for building more efficient computers we'll first have to establish metrics for comparison.

## Performance

There are mainly two metrics for measuring performance:

- <strong>Throughput</strong> : Number of operations/ unit time
- <strong>Latency</strong> : Time taken to complete one operation.

Contrary to what it might seem, throughput <strong>isn't</strong> simply the inverse of latency.

Example:

- If a website has two web servers for processing requests and it takes a single server 1 millisecond to process a single request (a server also cannot simultaneously process multiple requests at once), the latency is 1 millisecond whereas the throughput is 2000 (not 1000) since the throughput depends on how many servers the website uses. The throughput can also be further increased linearly by adding more servers without effecting the website's latency.
