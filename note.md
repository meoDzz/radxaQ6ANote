# Connection refused Window11

## 0. Check IP on radxa computer
```
hostname -I
```
## 1. Check SSH
```
sudo apt update
sudo apt install openssh-server -y
```
## 2. Check SSH
```
sudo systemctl start ssh
sudo systemctl enable ssh
```
## 3. Check status SSH
```
sudo systemctl status ssh
```
## 4. Connect to Radxa
```
ssh radxa@<radxaIP>
```
