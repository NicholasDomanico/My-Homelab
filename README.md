# My-Homelab

This is where I store my notes, diagrams, scripts, docker compose files, and anything else related to my homelab.

## The purpose of my lab

The main reason I got into homelabbing was to learn the fundamentals of computer networking and to practice cybersecurity concepts like log analysis and network security monitoring. It has started to go beyond this, as I am learning the benefits of self hosting services, from local file sharing to streaming music from my CD collection. However, this this is and always will be a cybersecurity-centric homelab.

## My hardware
---
- Desktop PC with Ryzen 7 3700X and 32GB DDR4 RAM. Running Debian Linux. Currently hosting Security Onion VM and Windows Server 2022 VM (KVM/QEMU), as well as single-node Wazuh docker container
- Beelink GK55 with 8GB RAM and Dual gigabit NICs. Running pfSense as router/firewall/VPN server.
- TP-Link TL-SG2008. Primary switch, cunnected directly to the pfSense LAN port.
- TP-Link TL-SG108E. Secondary switch, connected to primary switch via trunk port.
- TP-Link Archer A54 WiFi Router serving as access point.
- Raspberry Pi 5 8GB.
- Raspberry Pi 4 8GB. Running Portainer to manage docker containers in the lab.
- Raspberry Pi 4 4GB with a 1TB Wester Digital HDD in a USB connected enclosure. Running OpenMediaVault with NFS shares, as well as Dockerized Filegator for file sharing and Navidrome for music streaming.
- Orange Pi Zero 3 1GB with USB connected GPS reciever. Serving as an NTP server, using time data from GPS.
- Le Potato 2GB. Running Dockerized JuiceShop for wep app testing/bug bounty practice.
