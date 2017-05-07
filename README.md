How to setup VNC server (remote desktop to Linux) on Azure Ubuntu 14 Virtual Machine
==
#1. Create credentials

    vi /tmp/vnc.credentails

    VNCUSER=
    VNCPASSWD=

#2. Run the script
    
    sudo ./vnc.install

#3. Follow instructions for connection with Putty, by using tunnels. E.g.[this](https://www.digitalocean.com/community/tutorials/how-to-setup-vnc-for-ubuntu-12). Setup ssh tunnel localhost:5901 to 5901 and connect to localhost:5901 with TightVNC.
