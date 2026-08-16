# Scalability

## What is Scalability?

## Why Do We Need Scalability?

## Types of Scalability

## Common Bottlenecks

## Real-World Example

## Key Takeaways
Your Spring Boot application currently handles 1,000 requests/sec. Tomorrow traffic is expected to reach 50,000 requests/sec. How would you scale it?

"First, we would establish the workload characteristics and identify the current bottleneck. I'd look at CPU, memory, database utilization, request latency, throughput, network, and downstream dependencies. If the application tier is the bottleneck and is stateless, I'd horizontally scale the application behind a load balancer. Then I'd evaluate the database, caching, asynchronous processing, and other dependencies because scaling the application tier alone may simply move the bottleneck downstream."