**Monitor System Resources Using Netdata**

This project demonstrates how to install and run Netdata, a real-time, free, and open-source monitoring tool.
Netdata provides rich dashboards to visualize system and application performance metrics like CPU, memory, disk, and Docker containers.

****Objective**
**
Install and run Netdata quickly using Docker

Visualize system metrics in real time

Explore alerts, chart panels, and logs for monitoring

**Tools Used**

Netdata – Real-time monitoring and troubleshooting tool

Docker – To containerize and run Netdata easily

**Setup & Installation**

Run Netdata with Docker
Use the following command:
docker run -d --name=netdata -p 19999:19999 netdata/netdata

Access the dashboard
Open your browser and go to:
http://localhost:19999

**Features**

CPU Usage – Real-time usage and load averages

Memory Monitoring – RAM, cache, and swap details

Disk I/O – Reads, writes, and latency monitoring

Network Traffic – Incoming and outgoing packets/bytes

Docker Metrics – Per-container CPU, memory, and network usage

Alerts & Notifications – Pre-configured health checks

**Logs**

Netdata logs are available at:
/var/log/netdata
