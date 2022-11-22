---
sidebar: auto
---

# Installing Ubuntu Server on Raspberry Pi

This doc will guide you through installing ubuntu server on a raspberry pi

## Requirements
- GNU/Linux system
- A working memory card (16GB or more)

## Steps
1. Download the latest ubuntu server image
2. Download and install Raspberry Pi imager
3. Write the ubuntu image to memory card using raspberry pi imager
### Download the latest ubuntu server image

![Ubuntu Logo](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.neow.in%2Fnews%2Fimages%2Fuploaded%2F2022%2F03%2F1647455145_new-ubuntu-logo_story.jpg&f=1&nofb=1&ipt=6c049a0bbcc4738f1b01babd4701c62e32328e8b8783d92ebf935e11e6cde2a6&ipo=images)

Ubuntu is a Linux distribution based on Debian and composed mostly of free and open-source software. Ubuntu is officially released in three editions: Desktop, Server, and Core for Internet of things devices and robots. All the editions can run on the computer alone, or in a virtual machine.

Ubuntu Server for ARM includes everything you are looking for in a server operating system, including:
- The LXD container hypervisor, giving you instant access to isolated, secured environments running with bare metal performance
- Application container technology based on Docker and Kubernetes, including FAN-based networking
- SQL and NoSQL databases including CouchDB, MySQL, PostgreSQL, Redis and sqlite
- A wide collection of Web technologies, from HTTP servers to frameworks including Apache, Django, memcached, nginx, Wordpress and varnish

As Raspberry Pi uses the ARM64 architecture. We need to download the ARM64 version of ubuntu server image to run it on Raspberry Pi.
[Get Ubuntu Server (ARM64)](https://ubuntu.com/download/server/arm)

### Download latest version of Raspberry Pi imager

Raspberry Pi imager simpler way to image your microSD card with Raspbian, the official Raspberry Pi operating system, and other operating systems.
![Raspberry Pi Imager](https://www.raspberrypi.com/app/uploads/2020/03/RPI_intro-e1583228263677.png)

To install Raspberry Pi Imager. Open terminal in your GNU/Linux machine and type those following command (Ubuntu/Debian system).

```bash
sudo apt install rpi-imager
```
This command will download and install Raspberry Pi to your machine.


### Write the ubuntu image to memory card using raspberry pi imager
![SD Card](https://www.raspberrypi.com/app/uploads/2020/03/SD-READER-CU.jpg)

To write the freshly downloaded Ubuntu Server iso to your Raspberry Pi. First connect the Memory Card to your computer. Back up if any important file is on the card as it will erase and format everything on that card.

After that, Please follow the steps to write ubuntu to your card
1. Open Raspberry Pi Imager
2. Click "Choose OS" button
3. Select "Use Custom" from the PopUp menu
4. On the system file picker dialog, navigate and select ubuntu server iso.
5. Click "Choose Storage" button
6. Select your Raspberry Pi memory card
7. Click "Write" and wait for the write to complete

Voilla, You now have ubuntu server on your memory card. Insert the card on your Raspberry Pi and follow the on screen Instruction to complete the installation


---

This document is written by: **Shaman Sharif**
Edited by: **Shaman Sharif**
Creation Date: **22-Nov-2022**
Last Edit Date: **22-Nov-2022**
