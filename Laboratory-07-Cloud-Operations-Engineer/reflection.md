# Mission 7 Reflection

Checking the host server's resources is essential even when individual containers are functioning perfectly because containers share the underlying kernel and hardware resources of the host[cite: 3]. If the physical host runs out of RAM or disk space due to an external bottleneck, it will trigger kernel out-of-memory (OOM) killers, crashing all running containers regardless of their internal health. 

When users report login issues, the `docker logs` command provides granular visibility by recording every incoming request and server response code in real time[cite: 3]. By inspecting these logs, an engineer can instantly determine whether the request reached the application container, if it resulted in a client-side error (like a 401 or 403), or if an unhandled backend exception occurred[cite: 3].

There is a distinct operational difference between monitoring logs and monitoring metrics[cite: 3]. Monitoring logs (Checkpoint 4) involves analyzing discrete historical events, text strings, and HTTP request timelines to understand *what* happened and *why* an error occurred[cite: 3]. Conversely, monitoring metrics (Checkpoint 5) tracks numerical time-series data—such as CPU percentage, memory consumption, and network throughput—to gauge *how much* system capacity is currently being utilized[cite: 3].

To monitor thousands of containers simultaneously, large enterprise companies rely on centralized observability platforms like Prometheus for scraping time-series metrics and Grafana for visual dashboards and alerting[cite: 4]. These tools aggregate data across massive distributed clusters, automatically flagging anomalies before outages impact end users[cite: 4].

Overall, this laboratory activity significantly improved my ability to troubleshoot Linux environments by bridging the gap between infrastructure health checks, container deployment, traffic simulation, and data-driven log analysis[cite: 4]. I am now much more comfortable using native command-line diagnostics to verify system reliability[cite: 4].
