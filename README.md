# NetData-monitering-porject-7
 Monitor System Resources Using Netdata( Understand lightweight monitoring for servers or apps)

## ✅ Objective
Install Netdata and visualize real-time system and application performance metrics using Docker.

---

## 🛠️ Tools Used
- **Netdata** – Free, open-source, real-time monitoring tool  
- **Docker** – For containerizing and running Netdata easily

---

## 📦 Deliverables
- ✅ Netdata successfully running in a Docker container  
- ✅ Screenshot of Netdata dashboard showing system and container metrics  
- ✅ Exploration of logs and alerts

---

## 🚀 Mini-Guide: Getting Started

### 🐳 Step 1: Run Netdata via Docker
```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata

## 🌐 Step 2: Access the Dashboard
Open your browser and navigate to:
http://localhost:19999

🔍 What to Monitor

## Category	       ## Metrics Covered
System	            CPU, Memory, Disk I/O, Network, Load Average
Containers	        Docker stats per container (CPU, RAM, Disk, Net)
Alerts	            Warnings and critical alerts in real-time
Charts	            Interactive charts with 1-second resolution

# Logs to Explore
Inside the container:
  docker exec -it netdata bash
  cd /var/log/netdata
  ls
You will find logs like below 
error.log
access.log
health.log

From the host (optional):
  docker logs netdata

 ## 🎯 Outcome
By completing this task, you’ll gain an understanding of:
Lightweight and real-time monitoring with Netdata
Visualizing resource usage at system and container levels
Exploring health alerts and system logs

Dashboard Screenshot
Include a screenshot in the folder " proejct_evidence-of-completion "
