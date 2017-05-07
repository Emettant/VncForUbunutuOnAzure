Setup VNC server on Azure Ubuntu 14 Virtual Machine
==
#1. Create credentials:

    vi /tmp/vnc.credentails

    VNCUSER=
    VNCPASSWD=

#2. Give permissions to execute

    chmod +x vnc.install

#3. Run the script
    ./vnc.install

#4. Follow instructions for connection with Putty, by using tunnels. E.g. https://www.digitalocean.com/community/tutorials/how-to-setup-vnc-for-ubuntu-12
