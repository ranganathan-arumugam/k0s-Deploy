# How to Deploy Bold Reports in k0s Cluster with Redis and Nginx

The following steps guide you through the automated deployment of Bold Reports with Redis and Nginx servers.

## Prerequisites:
- Linux VM with 4 vCPU and 16 GB RAM (Ubuntu 20.04 or kernel v3.10 or newer).
- Managed Database server: PostgreSQL (pgsql), MySQL, or Microsoft SQL Server (mssql).

## Installation Steps:
Execute the following command on your Linux VM to install Bold Reports with Redis and Nginx. After the installation is completed, you can access Bold Reports on your machine's IP with port number 30080, and Redis on port 32379.

```bash
curl -sSLf https://raw.githubusercontent.com/ranganathan-arumugam/k0s-Deploy/main/deploy.sh | sudo bash
