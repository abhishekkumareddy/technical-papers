# Scaling

Scaling means increasing a system's capacity to handle more users or
requests.

## Horizontal Scaling

Adding more servers or instances to share the workload.

**Example:** Adding more servers when traffic increases.

## Vertical Scaling

Increasing the resources of an existing server, such as CPU or RAM.

**Example:** Upgrading a server from 4 GB RAM to 16 GB RAM.

![Horizontal and vertical
scaling](https://media.geeksforgeeks.org/wp-content/uploads/20260416101913435205/vertical_and_horizontal_scaling.webp)

**Reference:** [GeeksforGeeks --- Horizontal and Vertical
Scaling](https://www.geeksforgeeks.org/system-design/system-design-horizontal-and-vertical-scaling/)

------------------------------------------------------------------------

# Load Balancer

A load balancer distributes incoming requests across multiple backend
servers to prevent one server from becoming overloaded.

![Load balancer
diagram](https://media.geeksforgeeks.org/wp-content/uploads/20260112182015615865/load_balancer.webp)

## How It Works

1.  The load balancer receives incoming requests.
2.  It checks which servers are healthy.
3.  It forwards each request to a suitable healthy server.
4.  If a server is down, it avoids that server and uses another healthy
    server.

**Example:** Let us take the example that is we are running the three servers that is server A, server B and server c. If Server B is down, requests are sent to Server A or
Server C.

**Reference:** [GeeksforGeeks --- Load
Balancer](https://www.geeksforgeeks.org/system-design/what-is-load-balancer-system-design/)
