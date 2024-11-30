# ACMOS Project
## Mentor: Professor Sakshi Arora

### TEAM MEMBERS: </br>
YASH GUPTA (IMT2021514)  </br>
CHINMAY SULTANIA (IMT2021540)  </br>
DAKSH SHARMA (IMT2021533)   </br>
DIVYANSH SINGHAL (IMT2021522)   </br>


## Steps to obtain Tech Plots for IHP:

**Step 1:**

Install the Docker using the following commands:
```
sudo apt-get update
sudo apt-get install ca-certificates curl
sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc
# Add the repository to Apt sources:
echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
$(. /etc/os-release && echo "$VERSION_CODENAME") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
sudo docker run hello-world
```


if the commands gives you an error use the commands below:
```
sudo apt update
sudo apt upgrade -y
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y
docker --version
sudo systemctl status docker
sudo systemctl start docker
sudo systemctl enable docker
sudo docker run hello-world
```

**Step 2:**
Now clone the following Github repo using the given command:
```
git clone --depth=1 https://github.com/iic-jku/iic-osic-tools.git
```
**Step 3:**
Go to the iic-osic-tools directory using the following command:
```
cd iic-osic-tools/
```
*Option 1:* If you want to run on your browser, run the following command:

```
sudo ./start_vnc.sh
```

*Option 2:* If you want to run on your system locally, run the following command:

```
sudo ./start_shell.sh
```
**Step 4:** To finally open xschem, run the following command in docker terminal 

The terminal looks like this:
![term](https://github.com/user-attachments/assets/73145ffd-ef35-480c-8b45-bf2dc92665c2)

```
xschem &
```
 **OR**
 
```
xschem [filename].sch
```

Now, here are the testbenches for the NMOS and PMOS, you can draw the same for the techplots: </br>
**NMOS:** </br>
<img width="772" alt="Screenshot 2024-12-01 at 12 07 26 AM" src="https://github.com/user-attachments/assets/38992e56-679b-4f9c-893f-b5c57640bac4"> </br>

Netlist:
[Nmos.sch]()

**PMOS:** </br>
<img width="671" alt="Screenshot 2024-12-01 at 12 09 05 AM" src="https://github.com/user-attachments/assets/c1bba4e4-01f5-4eaa-8942-9a07581f3feb"> </br>



**Plots:**

![IMG-20241129-WA0008](https://github.com/user-attachments/assets/d9fa7c9e-80bf-49f9-bece-832502ea5b9f)
![IMG-20241129-WA0009](https://github.com/user-attachments/assets/c5a28f01-fd08-46cb-83d2-43a9c4d8bbef)
![IMG-20241129-WA0010](https://github.com/user-attachments/assets/a596b662-5270-42f5-b679-da606cd2aa2d)
![IMG-20241129-WA0011](https://github.com/user-attachments/assets/629f28d4-5267-44b3-ae25-5743f85c9897)
![IMG-20241129-WA0012](https://github.com/user-attachments/assets/727bcebb-4ec4-4642-8581-ba8db3d8ff32)
![IMG-20241129-WA0013](https://github.com/user-attachments/assets/ec196bc6-416d-46a7-9961-2b30db576cff)

**Tech Plots** </br>

NMOS:
![nmos_idw](https://github.com/user-attachments/assets/fe40e69c-72b4-498e-8f8e-8745df8722d2)
![nmos_gmro](https://github.com/user-attachments/assets/2b8ae0ee-4158-4bcf-b75e-4e3df4f67413)
![2](https://github.com/user-attachments/assets/7b962c37-1717-457b-a8ea-d627e8bbbf73)

 </br>
 
PMOS:

![pmos_d](https://github.com/user-attachments/assets/0522bfae-0df7-4e71-b3bf-34c8d571b5ea)
![pmos_gmro](https://github.com/user-attachments/assets/87a8c7b3-b650-4871-96fa-03a94ccd02d4)
![2](https://github.com/user-attachments/assets/174b38de-6a7a-4e7c-9c46-39b4d1c6f8af)


## IHP
![WhatsApp Image 2024-11-30 at 04 32 05](https://github.com/user-attachments/assets/96607a2c-2f74-40df-8fbe-e4341b5b4810)


