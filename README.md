# Diode

### 🔹 1. Let's update the general system
```
sudo apt update && sudo apt upgrade -y
```

### 🔹 2. Check if Snap Package Manager is Installed
(Usually pre-installed in Ubuntu, but let's make sure)
```
sudo apt install snapd -y
```


### 🔹 3. Diode Node Paketini Kur
```
sudo snap install diode-node
```
After installation, diode-node starts running in the background.


### 🔹 4. Install Diode Node Package
```
diode-node.info
```
This command shows information about your node such as its identity, connected network, and operational status.

![image](https://github.com/user-attachments/assets/5880003f-19c9-42fc-88ce-493327a5e75a)


### 🔹 5. Example Web Broadcast with Diode Client (Optional)
If you want to broadcast a directory over the Diode Network:
```
mkdir mysite
echo "Hello Diode" > mysite/index.html
diode publish mysite
```
After this process, you'll get a unique .diode.link URL. You can visit this address in your web browser to view the content.

### 🔹 6. (Optional) Monitor Logs to Keep Node Running Continuously
```
journalctl -u snap.diode-node.daemon -f
```
With this command, you can monitor the background node logs.

### 🔹 7.Connect to Platform and Link Wallet

- Visit https://diodenetwork.io/app/  and create/connect a new EVM wallet

### 🔹 8. Download Diode Collab Desktop App

https://diode.io/joinzone/#close

- Click Get App on the upper right corner

![image](https://github.com/user-attachments/assets/625589b0-4a88-42de-a6dc-473c5ed415aa)



### 🔹 9. Join Zone Code
It may take a while to sync, wait patiently.
```
p0xUHtufRS_tMNd9XRvnxbMmXPtOyRbPrQLnLN4j3VNsDhwSrpRYpwbnhMZ2
```

![joincode-entry-example](https://github.com/user-attachments/assets/0a61fb5e-af27-4f0b-9ddc-001c33b455b2)



### 🔹 10. APost the participation code below into the registrar channel shown in the image. After entering this code, it’ll ask if you accept—type I Accept to proceed. Once accepted, you'll receive a personal invite code that you can use to invite others.
```
IZZLEWCHDRGDTZTRGTTH
```

![image](https://github.com/user-attachments/assets/52afa1d9-fc94-423b-89dd-64cab864e279)


### 🔹 11. Take the wallet address you connected on the platform and register it by typing the following to the bot, as shown in the image:
```
set wallet EVMCUZDANADRESINIZ
```
![image](https://github.com/user-attachments/assets/8b5d8329-a5ee-4693-8565-bc472552e34b)


### 🔹 13. Register your running node like the example below. The part labeled NODEID can be found from the diode-node.info command output. I’ve added an example below. You can name NODEALIAS however you like. You can register as many nodes as you want—there are no limits.
```
register node NODEID NODENAME
```
![image](https://github.com/user-attachments/assets/22dd0c02-cfec-4188-b5ab-7133938685c7)


![image](https://github.com/user-attachments/assets/0075b3a1-f4ea-4f93-ad02-740094562a80)

### 🔹 14. Both of the following links should work fine. It may appear like the first one. You can also continue from https://diodenetwork.io/app/.

![image](https://github.com/user-attachments/assets/744efc57-1ed9-44c9-aedf-a7213da7557d)

![image](https://github.com/user-attachments/assets/1d1b8092-7e8f-41ff-bcc8-c77895c234e7)


### 🔹 15. Some Useful Server Commands

```snap install diode-node``` - to install

```diode-node.info``` -  to see node info

```snap restart diode-node``` - to restart the node

```sudo snap logs diode-node -f``` - to view logs

### 🔹 16. Some Useful Diode Collab Registrar Channel Commands

```stats``` - to view your general info

```list nodes``` -  to view all your registered nodes

###  Join tg, I will post bots there too.
T.me/getcakedieyoungx


### For donations and buying me a coffee:
EVM: 0xE065339713A8D9BF897d595ED89150da521a7d09

SOLANA: CcBPMkpMbZ4TWE8HeUWyv9CkEVqPLJ5gYe163g5SR4Vf








