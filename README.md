# FORTYTWO NODE SET UP GUIDE
This guide will walk you through the process of setting up a @fortytwonetwork node on WSL or any Linux based environment

## NOTE: You have to be invited before running this node. This node will only run a gpu system.

## Fill form to get invited: https://tally.so/r/wQzVQk

personally, i run my node on a rented a gpu on [quickpod](https://console.quickpod.io/templates) 
you can head to; (https://console.quickpod.io/templates) 
* Sign up
* Choose from the available GPUs you can afford and create a POD
* Navigate to "my pods" and connect to your system via web

# SYSTEM REQUIREMENTS
![Image](https://github.com/user-attachments/assets/5462ed3e-2d65-417e-8f94-293a70336b9f)

# GETTING STARTED
## Installing Prerequisites

## 1. Install unzip:
```bash
apt update && apt install unzip -y
```

## 2. Install screen:
```bash
apt update && apt install screen -y
```

## 3. Install psmisc:
```bash
apt update && apt install psmisc -y
```

## 4. Install libgomp1:
```bash
apt update && apt install -y libgomp1
```

## 5. Install curl:
```bash
apt update && apt install -y curl unzip
```
# RUNNING THE NODE

## 6. Create a Fortytwo Directory:
```bash
mkdir -p ~/Fortytwo && cd ~/Fortytwo
```
## 7. Run the following commands to download the node package, extract it, and execute the installation script:
```bash
curl -L -o fortytwo-console-app.zip https://github.com/Fortytwo-Network/fortytwo-console-app/archive/refs/heads/main.zip
unzip fortytwo-console-app.zip
cd fortytwo-console-app-main
chmod +x linux.sh && ./linux.sh
```

