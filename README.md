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

## 8. As a new user, select option 1:
![Image](https://github.com/user-attachments/assets/46c8648a-9f18-4fd3-8fb7-9177a248d473)

## 9. Input the Activation Code you received from the invite mail:
![Image](https://github.com/user-attachments/assets/b86dcfce-70db-46b0-8596-a005eba1bbf2)
![Image](https://github.com/user-attachments/assets/74c1aebe-78af-4dd1-8258-04fbf8841f79)

## 10. Select "0" or Hit The Enter Key To Auto-Select a Model (Recommended)
![Image](https://github.com/user-attachments/assets/01ffc2ad-ac32-48e1-a680-e18516a93ca7)

# 11. NODE STARTED SUCCESSFULLY 
## IF YOU SEE THIS, YOU'RE GOOD. GO TO THE NEXT STEP
![Image](https://github.com/user-attachments/assets/41b0ffb8-8f21-48bc-aea6-1865423706bd) 

## 12. STOP NODE
`ctrl` + `c`

# RUNNING THE NODE IN A SCREEN:
## 13. CREATE SCREEN:
```bash
screen -S Fortytwo

## RUN THE NODE STARTUP SCRIPT
```bash
./linux.sh
```
## 14. CLOSE THE SCREEN:
`ctrl` + `A` + `D`

## THAT'S ALLFOR NOW, A RESTART GUIDE FOR EXISTING USERS WILL BE UPDATED SOON
## G42 💜
